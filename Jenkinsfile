pipeline {
    agent any
    triggers {
        pollSCM('H * * * *')
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
        stage('slack') {
            steps {
                slackSend channel: '#general', message: 'This is for Jenkins'
            }
        }
    }
}