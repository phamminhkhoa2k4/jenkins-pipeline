pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                cleanWs()
            }
        }
        stage('Checkout') {
            steps {
                git branch: 'main', 
                    url: 'https://github.com/phamminhkhoa2k4/jenkins-pipeline.git'
            }
        }
    }
}
