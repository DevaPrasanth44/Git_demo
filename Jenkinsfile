pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/DevaPrasanth44/Git_demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build stage started"
            }
        }

        stage('Test') {
            steps {
                echo "Testing application"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application"
            }
        }
    }
}
