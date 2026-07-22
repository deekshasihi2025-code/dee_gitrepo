pipeline {
    agent {
        label 'slave'
    }

    stages {
        stage('Check Agent') {
            steps {
                sh 'hostname'
                sh 'whoami'
                sh 'pwd'
            }
        }
    }
}
