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

    
