pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker-compose build'
            }
        }
        stage('Test') {
            steps {
                sh 'docker-compose up -d'
                // Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                // Add deployment commands here
            }
        }
    }
}
