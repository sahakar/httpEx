pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Hello world!' 
                
               
                bat "mvn  clean"
            }
        }
        stage('Compile') {
            steps {
                
                bat "mvn  install"
            }
        }
        stage('Test') {
            steps {
                
                 echo 'Test Completed!' 
            }
        }
        stage('Deploy') {
            steps {
                
            bat "mvn deploy"
            }
        }
    }
}