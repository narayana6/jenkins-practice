pipeline {
    agent {
        label 'Agent-1'
    }
    options {
        timeout(time: 1, unit: 'SECOUND')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo This is Build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo This is Test'
            }
        }
        stage('Deploy') {
            steps {
               sh 'echo This is Deploy'
            }
        }
    }
}
