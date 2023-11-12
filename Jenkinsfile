pipeline {
    agent any
    triggers {
        pollSCM('*/3 * * * *')
    }
    stages {
        stage('test') {
            steps {
                cat README.md
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