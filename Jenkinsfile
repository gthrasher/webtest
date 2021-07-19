pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                echo 'Building...'
                sh 'python --version'
            }
        }
        stage('test'){
            steps {
                echo 'Testing...'
            }
        }
        stage('deploy'){
            steps{
                echo 'Deploying...'
            }
        }
    }
}
