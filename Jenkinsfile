pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/K3nleyy/Test2'
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
                echo 'Deploying the project...'
            }
        }
    }
}
