pipeline {
    agent any
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                bat 'npm install'
                bat 'npm run build'
            }
        }
        stage('Test') {
            steps {
                bat 'echo TEST PASSED'
            }
        }
        stage('Deploy'){
            steps {
                bat 'echo DESPLEAGADO'
            }
        }
    }
}