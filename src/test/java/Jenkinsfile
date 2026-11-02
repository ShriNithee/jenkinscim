pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/akasha66850-cloud/Jenkins-CI-Demo.git'
            }
        }

        stage('Build and Test') {
            steps {
                bat 'mvn clean test'
            }
        }
    }
}
