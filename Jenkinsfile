pipeline {
    agent any
    triggers {
        pollSCM('*/1 * * * *')
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