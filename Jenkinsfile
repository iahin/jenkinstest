pipeline {
    agent any
    stages {
        stage('Initialize') {
            steps {
                echo 'Initializing..'
                bat python pip install -r requirements.txt
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}