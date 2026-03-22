pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/kavazik1/nodejs-jenkins-demo.git'
            }
        }

        stage('Run App') {
            steps {
                sh 'node index.js'
            }
        }

    }
}
