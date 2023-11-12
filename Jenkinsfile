pipeline {
    agent any
    triggers {
        pollSCM('*/3 * * * *')
    }
    stages {
        stage('test') {
            steps {
                ls
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