pipeline {
    agent any 

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning Repository...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building Application...'
                // Example: sh './mvnw clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Running Tests...'
                // Example: sh './mvnw test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to Server...'
                // Example: sh './deploy.sh'
            }
        }
    }
}
