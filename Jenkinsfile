pipeline {
    agent {
        docker { image 'openjdk:8-jre-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'java -version'
            }
        }
    }
}