pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/eamanze/application-repo.git'
            }
        }

        stage('Build') {
            steps {
                // Your build steps go here
                sh 'echo "Building..."'
            }
        }

        stage('Archive') {
            steps {
                // Your archive steps go here
                sh 'echo "Archiving..."'
            }
        }
    }
}

properties([
    pipelineTriggers([
        pollSCM('H/15 * * * *') // Poll SCM every 15 minutes
    ])
])
