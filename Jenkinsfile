pipeline {
    agent any
    stages {
        stage('Clean') {
            stepes {
                sh 'mvn clean'
            }
        }
        stage('Test') {
            stepes {
                sh 'mvn test'
            }
        }
        stage('Package') {
            stepes {
                sh 'mvn package'
            }
        }
    }
}