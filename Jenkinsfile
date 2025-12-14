pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/DevaPrasanth44/Git_demo'
            }
        }

        stage('Build') {
            steps {
                echo 'HTML build completed'
            }
        }

        stage('Deploy') {
            steps {
                bat '''
                xcopy /E /Y *.html C:\\inetpub\\wwwroot\\
                '''
            }
        }
    }
}
