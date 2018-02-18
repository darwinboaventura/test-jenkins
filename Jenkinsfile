pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('Should show npm version') {
            steps {
                sh 'npm --version'
            }
        }
    }
}