pipeline {
    agent any

    stages{
        stage('checkout ') {
            steps{
                echo "validate maven"
                bat 'mvn -v'
            }
        }
        
        
        
        
        
        stage('git credensial') {
           steps{
               git credentialsId: 'TOKEN-GIT', url: 'https://github.com/rritsoft/maven1.git'
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
    
    
    
       
    
    
    
    
    
    
    
    
    
    
    
    }

























    
}
