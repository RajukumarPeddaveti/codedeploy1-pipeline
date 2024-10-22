pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building..."'
                sh 'mvn clean package' // Example build step
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying..."'
                // Add your deployment steps here
            }
        }
    }
}
