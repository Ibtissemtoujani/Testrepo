pipeline {
    agent {
        docker { image 'nginx-image' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'sudo apt install lsb_release'
                sh 'lsb_release -a'
            }
        }
    }
}
