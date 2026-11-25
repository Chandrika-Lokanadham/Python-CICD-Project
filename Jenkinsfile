pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Python Application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Python Application'
                sh 'python -m pytest'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application Deployment Successful'
            }
        }
    }
}