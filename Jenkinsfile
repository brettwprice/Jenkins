pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('Do Something') {
            steps {
                sh 'echo "Do Something"'
            }
        }
        stage('Poo Face') {
            steps {
                sh 'echo "Poo Face"'
            }
        }
    }
}
