pipeline {
    agent { docker { image 'node:20.9.0-alpine3.18' } }
    triggers {
        pollSCM '*/3 * * * *'
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