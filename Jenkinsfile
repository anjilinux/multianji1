pipeline {
    agent any

    stages{
        
        
         
        stage('git credensial') {
           steps{
               git credentialsId: 'TOKEN-GIT', url: 'https://github.com/rritsoft/maven1.git'
           }
       }  
    
        
        
        
        
        
        
        stage('validate ') {
            steps{
                echo "validate maveni"
                bat 'mvn -v'
            }
        }
        
        
        

        
        
        stage('checkout. ') {
            steps{
                echo "validate maveno"
                bat 'mvn -v'
            }
        }
        
        
        

    
        
        stage('checkout1 ') {
            steps{
                echo "validate maven11"
                bat 'mvn -v'
            }
        }
        
        
        

        
        
        
        
        stage('clean test') {
            steps{
                bat 'mvn test'
            }
        }
    
        stage('clean package') {
            steps{
                bat 'mvn package'
            }
        }   
    
        stage('install') {
            steps{
                bat 'mvn install'
            }
        }
    
        
        
          
        stage('clean testq') {
            steps{
                bat 'mvn test'
            }
        }
    
        stage('clean packageq') {
            steps{
                bat 'mvn package'
            }
        }   
    
        stage('installq') {
            steps{
                bat 'mvn install'
            }
        }
    
    
    
      
        stage('clean test3') {
            steps{
                bat 'mvn test'
            }
        }
    
        stage('clean package3') {
            steps{
                bat 'mvn package'
            }
        }   
    
        stage('install4') {
            steps{
                bat 'mvn install'
            }
        }
    
    
       
    
    
    
    
      
        stage('clean test5') {
            steps{
                bat 'mvn test'
            }
        }
    
        stage('clean package55') {
            steps{
                bat 'mvn package'
            }
        }   
    
        stage('install56') {
            steps{
                bat 'mvn install'
            }
        }
    
    
    
    
    
    
    
    
    }

























    
}
