# Jenkinsfile

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Insert build commands here (e.g., compile your code)
                    echo 'Building the application...'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    // Insert deployment commands here (e.g., deploy to EC2, Lambda)
                    echo 'Deploying the application...'
                }
            }
        }
    }
}
