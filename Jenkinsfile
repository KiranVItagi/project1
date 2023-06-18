pipeline {
    agent none 
stages {
    agent { label 'slave1' }
        stage('checkout') {
            steps {
                sh 'echo checkout step'
            }
        }
    }
}
