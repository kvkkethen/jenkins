pipeline {
    agent any
    
    stages {
        stage('install docker') {
            steps {
                sh 'sudo yum install -y docker'
            }
        }
        stage('start docker') {
            steps {
                sh 'sudo systemctl enable docker.service'
            }
        }
        stage('status docker') {
            steps {
                
                sh 'sudo systemctl status docker'
            }
        }
        stage('pull image') {
            steps {
                sh 'sudo docker pull nginx'
            }
        }
        stage('run container') {
            steps {
                sh 'sudo docker run -it -d -p 8000:80 nginx'
            }
        }
        stage('final message') {
            steps {
                echo 'Welcome to nginx'
            }
        }
    }
}
[3:47 pm, 26/03/2024] +91 86608 63293: pipeline {
    agent any
    
    stages {
        stage('install docker') {
            steps {
                sh 'sudo yum install -y docker'
            }
        }
        stage('start docker') {
            steps {
                sh 'sudo systemctl enable docker.service'
            }
        }
        stage('status docker') {
            steps {
                
                sh 'sudo systemctl status docker'
            }
        }
        stage('pull image') {
            steps {
                sh 'sudo docker pull nginx'
            }
        }
        stage('run container') {
            steps {
                sh 'sudo docker run -it -d -p 8000:80 nginx'
            }
        }
        stage('final message') {
            steps {
                echo 'Welcome to nginx'
            }
        }
    }
}
