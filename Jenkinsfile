pipeline {
    agent {
        docker {
            image 'ubuntu'
            label 'ubuntu'
            args  '-v /tmp:/tmp'
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