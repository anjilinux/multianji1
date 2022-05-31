pipeline {
    agent any
    stages {
        stage('maven validate') {
            steps{
               bat 'mvn -v'
            }
        
        }
    
        stage('pom.xml-from') {
            steps{
               git credentialsId: 'TOKEN-GIT', url: 'https://github.com/rritsoft/multianji1.git'
            }
        }
    
    
         stage('clean test'){
             steps{
                 bat 'mvn clean test'
             }
         }
    
        stage('clean package'){
            steps{
                bat 'mvn clean package'
            }
        }
    
       
       
       
        stage('clean install'){
            steps{
                bat 'mvn clean install'
            }
        }


        stage('report testall'){
           steps{
               cucumber buildStatus: 'null', customCssFiles: '', customJsFiles: '', failedFeaturesNumber: -1, failedScenariosNumber: -1, failedStepsNumber: -1, fileIncludePattern: '**/*.json', pendingStepsNumber: -1, skippedStepsNumber: -1, sortingMethod: 'ALPHABETICAL', undefinedStepsNumber: -1
           }
       }




    }
}
