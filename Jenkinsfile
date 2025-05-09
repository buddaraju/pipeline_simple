pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo This is build'
            }
        }
        stage('Test') {
            steps {
                sh 'test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'deploy'
            }
        }
    }
}
