pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('build2') {
            steps {
                sh 'python --version'
            }
        }
    }
}
