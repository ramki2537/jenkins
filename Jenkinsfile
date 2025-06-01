pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    sh """
                      echo "This is first build pipeline script"
                    """
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    sh """
                      echo "This is first test pipeline script"
                    """
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    sh """
                      echo "This is first deploy pipeline script"
                    """
                }
            }
        }
    }
}