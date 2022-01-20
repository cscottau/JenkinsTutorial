pipeline {
    agent { docker.image('python:3.10.1-alpine').inside("""--entrypoint=''""") {}}
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
