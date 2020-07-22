pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'docker run hello-world'
                sh 'node --version'
            }
        }
    }
}
