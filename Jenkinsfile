pipeline {
    agent any

    stages {
        stage('Install Node') {
            steps {
                sh '''
                whoami
                sudo apt-get update
                sudo apt-get install -y nodejs npm
                '''
            }
        }

        stage('Run App') {
            steps {
                sh 'node index.js'
            }
        }
    }
}
