pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''echo bulding maven app
                   '''
            }
        }
        stage('test') {
            steps {
                sh 'echo testing app with some changes'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo deploying app with some changes'
            }
        }
    }
}
