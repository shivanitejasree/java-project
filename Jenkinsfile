pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning repo...'
                // Git auto-checkout is handled by Jenkins
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'mvn clean install' // Or any build command
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'echo Running tests...' // Replace with actual test commands
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'echo Deploy step...' // Add deploy logic here
            }
        }
    }
}
