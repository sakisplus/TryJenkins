pipeline {
    agent any
    triggers {
        pollSCM('H/0 * * * *')
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
                slackSend channel: '#automations', message: 'This is for Jenkins'
            }
        }
    }
}