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
    
    
    
       
    
    
    
    
    
    
    
    
    
    
    
    }

























    
}
