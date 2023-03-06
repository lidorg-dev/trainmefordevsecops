pipeline {
    agent any

    stages {
        stage('Git Clone') {
            steps {
                    checkout scmGit(branches: [[name: 'email-notification']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/lidorg-dev/trainmefordevsecops.git']])

                }
        }
        stage('SAST') {
            steps {
                    sh ''
                }
            }
        stage('Build and Tag ') {
            steps {
                     sh ''
                }
        }
        stage('Image and Vulnerabilty Scan ') {
            steps {
                     sh ''
                }
        }
        stage('Post to Docker Hub  ') {
            steps {
                     sh ''
                }
        }
        stage('Pull image Server  ') {
            steps {
                     sh ''
                }
        }
        stage('DAAST  ') {
            steps {
                     sh ''
                }
        }
    }
}
