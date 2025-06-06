pipeline {
    agent { label 'agent-1' }
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
    post {
        always {
            echo "I will always say Hello again!"
        }
        failure {
            echo "I will run when pipeline is failed"
        }
        success {
            echo "I will run when pipeline is success"
        }
    }
}