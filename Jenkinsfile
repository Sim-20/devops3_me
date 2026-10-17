
pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }

        stage('Run Python App') {
            steps {
                sh 'python app.py'
            }
        }
    }
}
