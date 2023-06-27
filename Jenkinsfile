pipeline {
    agent { docker { image 'python:3.17-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
