pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                script {
                    checkout scm
                }
            }
        }

        stage('Build') {
            steps {
                script {
                   // Your build commands or scripts
                    echo 'Building the artifact...'
                }
            }
        }
        stage('Deploy') {
            steps {
                // Deploy the artifact to a production environment
                 echo 'Deploy successful!'
            }
        }

    }

    }
