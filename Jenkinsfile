
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/ShriNithee/jenkinscim.git'
            }
        }

        stage('Build and Test') {
            steps {
                bat 'echo Building project'
                bat 'echo Testing project'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying project'
            }
        }
    }
}
