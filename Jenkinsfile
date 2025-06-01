pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/AnhQuy6/QuyHTA_Demo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
