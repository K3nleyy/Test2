pipeline{
    agent any
    stages{

        stage('checkout'){
            git 'https://github.com/K3nleyy/Test2'
        }
        stage('Build'){
            echo 'Building the application'
        }

        stage('Test'){
            echo 'Testing the application'
        }

        stage('Deploy'){
            echo 'Deploying the application'
        }
    }
}
