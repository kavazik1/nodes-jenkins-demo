pipeline {
    agent any

    stages {
        stage('Install Node') {
            steps {
                sh '''
                apt-get update
                apt-get install -y nodejs npm
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
