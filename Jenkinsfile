pipeline {
    agent {
        docker { image 'nginx-image' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
