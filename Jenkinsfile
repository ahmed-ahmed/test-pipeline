pipeline {
    environment {
        BUILD_HOME='/var/lib/jenkins/workspace'
    }
    agent any
    stages {
        stage('Checkout: Code') {
            steps {
                sh "echo 'checkout step started'"
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}
