pipeline {
    agent any 
    stages {
        stage('checkout') {
            steps {
                echo "hello ${env.BRANCH_NAME}"
                sh 'ls -a'
            }
        }
    }
}