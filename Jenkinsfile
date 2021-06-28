pipeline {
    agent {
        docker { image 'nginx-image' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'lsb_release -a'
            }
        }
    }
}
