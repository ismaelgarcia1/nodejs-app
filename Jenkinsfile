pipeline {
    agent any 
    stages {
        stage('checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/ismaelgarcia1/nodejs-app.git']]])
                echo 'checkout'
            }
        }
    }
}