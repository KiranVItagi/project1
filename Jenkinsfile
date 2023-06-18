pipeline {
    agent none 
stages {
          stage('checkout') {
                agent { label 'slave1' }
            steps {
                sh 'echo checkout step'
            }
        }
    }
}
