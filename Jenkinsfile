pipeline {
    agent any
    triggers {
        pollSCM('*/15 * * * *')
    }
    stages {
        stage('test') {
            steps {
                echo 'Step test'
            }
        }
        stage('build') {
            steps {
                echo 'Step build'
            }
        }
        stage('hello') {
            steps {
                echo 'Say hello'
            }
        }
    }
}