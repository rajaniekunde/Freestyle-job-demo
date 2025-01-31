pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/rajaniekunde/Freestyle-job-demo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project GLOBALLOGIC'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
