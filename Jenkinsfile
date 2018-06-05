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
        stage('Run: Code') {
            steps {
                sh "node index.js"
            }
        }

    }
    post {
        always {
            cleanWs()
        }
    }
}
