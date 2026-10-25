pipeline {
    agent any

    triggers {
        pollSCM('H/5 * * * *')
    }

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checkout successful'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage executed - version2'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage executed'
            }
        }
    }
}
