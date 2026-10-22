
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'Source code checked out from GitHub.'
            }
        }

        stage('Build Information') {
            steps {
                echo 'Preparing Experiment 5 CI/CD pipeline.'
                sh 'ls -la'
            }
        }
    }

    post {
        success {
            echo 'Initial pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Check the console output.'
        }
    }
}
