pipeline {
    agent {
        docker {
            label 'master'          // node có SSH credential tới host remote
            image 'node:18-alpine'
            registryCredentialsId 'ssh-credential-id' // credential SSH đã tạo
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'node -v'
            }
        }
    }
}
