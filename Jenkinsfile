pipeline {
    agent { 
        docker 'cvcbrasil/nginx-singlepage:log' 
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}