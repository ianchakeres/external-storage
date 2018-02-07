pipeline {
    agent any
    stages {
        stage('Build and Test') {
            steps {
                sh "printenv"
                sh "go env"
                sh "./test.sh"
            }
        }
    }
}
