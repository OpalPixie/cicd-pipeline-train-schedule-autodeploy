pipeline {
    agent any
    environment {
        //be sure to replace "bhavukm" with your own Docker Hub username
        DOCKER_IMAGE_NAME = "bhavukm/train-schedule"
    }
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh 'sudo chmod +x gradlew'
                
            }
        }
        stage('Build Docker Image') {
            when {
                branch 'master'
            }
            steps {
                script {
                    
                    }
                
            }
        }
        stage('Push Docker Image') {
            when {
                branch 'master'
            }
            steps {
                script {
                    
                    }
                }
            }
        
        stage('CanaryDeploy') {
            when {
                branch 'master'
            }
            environment { 
               
            }
            steps {
                
                
            }
        }
        stage('DeployToProduction') {
            when {
                branch 'master'
            }
            environment { 
                
            }
            steps {
               
               
            }
        }
    }
}
