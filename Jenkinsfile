pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                sh '/opt/maven/bin/mvn clean'
            }
        }
        stage('Test') {
            steps {
                sh '/opt/maven/bin/mvn test'
            }
        }
        stage('Package') {
            steps {
                sh '/opt/maven/bin/mvn package'
            }
        }
    }
}
