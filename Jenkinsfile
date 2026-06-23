pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building using Jenkinsfile...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing using Jenkinsfile...'
            }
        }
    }
}