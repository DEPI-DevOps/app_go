pipeline {
    agent any
    stages {
        stage('Building image') {
            steps {
                sh """
                sudo docker build -t sh3b0/app_go .
                """
            }
        }
    }
}
