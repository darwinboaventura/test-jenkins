pipeline {
    agent { 
        docker {
            image 'cvcbrasil/nginx-singlepage:log'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}