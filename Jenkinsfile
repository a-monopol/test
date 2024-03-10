pipeline {
    agent {
        docker {
            image 'ubuntu'
        }
    }

    stages {
        stage('Hello') {
            steps {
                sh 'cat /etc/os-release'
            }
        }
    }
}