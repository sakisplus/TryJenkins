pipeline {
    agent any
    triggers {
        pollSCM('*/1 * * * *')
    }
    stages {
        stage('test') {
            steps {
                sh 'node --version'
            }
        }
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}