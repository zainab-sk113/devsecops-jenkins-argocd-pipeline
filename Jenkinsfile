pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t devsecops-app .'
            }
        }

        stage('Security Scan') {
            steps {
                sh 'trivy image devsecops-app'
            }
        }

    }
}
