pipeline {
    agent any 
    stages {
        stage('checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/ismaelgarcia1/nodejs-app.git' 
                echo 'checkout'
            }
        }
    }
}