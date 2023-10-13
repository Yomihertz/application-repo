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
    }

    post {
        success {
            echo 'Build successful! Add additional post-build steps here.'
        }
    }
}
