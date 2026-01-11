pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo "Fetching code"
            }
        }
        stage('Build Docker Image') {
            steps {
                echo "docker build -t demo-app ."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy to cloud server"
            }
        }
    }
}
