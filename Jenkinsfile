pipeline {
    agent any 
    stages {
        stage('checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/ismaelgarcia1/nodejs-app.git']]])
                echo 'checkout'
            }
        }
    }
}