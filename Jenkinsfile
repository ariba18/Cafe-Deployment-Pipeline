pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/ariba18/Cafe-Deployment-Pipeline.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Cafe Deployment Pipeline'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Application'
            }
        }
    }
}