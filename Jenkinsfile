pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Example build commands
                // Windows: bat 'echo Building project...'
                // Linux/Mac: sh 'echo Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example test commands
                // Windows: bat 'echo Running tests...'
                // Linux/Mac: sh 'echo Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Example deploy commands
                // Windows: bat 'echo Deploying project...'
                // Linux/Mac: sh 'echo Deploying project...'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished (cleanup or notifications here)'
        }
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
