pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mkdir jenkinstest'
                echo 'Directory Created..'
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
