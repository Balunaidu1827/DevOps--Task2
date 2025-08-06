pipeline {
    agent any

    environment {
        IMAGE_NAME = 'sample-app:latest'
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Balunaidu1827/DevOps--Task2'
            }
        }

        stage('Build Docker Image') {
            steps {
                script {
                    docker.build("${IMAGE1}")
                }
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the Docker image ${IMAGE1}"
                
            }
        }
    }
}
