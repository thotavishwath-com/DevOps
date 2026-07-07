pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // This pulls the code from your GitHub repo
                git branch: 'main', url: 'https://github.com/noshankjain/devops.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
