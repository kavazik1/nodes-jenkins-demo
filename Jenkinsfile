pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/kavazik1/nodes-jenkins-demo.git'
            }
        }

        stage('Run App') {
            steps {
                sh 'node index.js'
            }
        }

    }
}
