pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Use the Jenkins 'git' step to clone the repository
                git url: 'https://github.com/neerajddun/jenkins-pipeline.git'
            }
        }

        stage('Docker Image') {
            steps {
                script {
                    // Build a Docker image using the Dockerfile in the repository
                    // You can replace 'mydockerimage' with any preferred image name
                    docker.build('mydockerimage')
                }
            }
        }

        stage('Deploy') {
            steps {
                echo 'Hello India'
            }
        }
    }
}
