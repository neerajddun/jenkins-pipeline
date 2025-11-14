pipeline {

    agent any 

    stages {

        stage ('Checkout') {

            steps {

            }
        }

        stage ('Docker Image') {
            
            steps {

             script {

                docker.build("dockerfile")
             }
            
            }
        }

        stage ('Deploy') {

            steps {

                echo 'Hello India'
            }
        }
    }

    pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Example SCM checkout step
                checkout scm
            }
        }

        stage('Docker Image') {
            steps {
                script {
                    // Replace "myimage" with your desired image name
                    docker.build("mydockerimage")
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

