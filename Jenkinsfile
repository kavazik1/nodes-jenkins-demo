pipeline {
    agent any

    stages {
        stage('Run App') {
            steps {
                sh '''
                curl -fsSL https://deb.nodesource.com/setup_18.x | bash -
                apt-get install -y nodejs
                node index.js
                '''
            }
        }
    }
}
