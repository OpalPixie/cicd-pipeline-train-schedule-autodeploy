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
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Install Puppet'
                sh "wget -N -O 'puppet.deb' https://apt.puppetlabs.com/puppet6-release-bionic.deb"
                sh "chmod 755 puppet.deb"
                sh "sudo dpkg -i puppet.deb"
                sh "sudo apt update"
                sh "sudo apt install -y puppet-agent"
                
            }
        }
        stage('Push Docker Image') {
            steps {
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
            }
        }
        stage('CanaryDeploy') {
            when {
                branch 'master'
            }
            
            steps {
             echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                
            }
        }
        stage('DeployToProduction') {
            when {
                branch 'master'
            }
            
            steps {
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation'
                echo 'Running build automation' 
               
            }
        }
    }
}

