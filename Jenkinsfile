pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Run Test') {
            steps {
                echo 'Running test script...'
                bat 'echo Hello QA from Jenkins'
            }
        }

        stage('Result') {
            steps {
                echo 'Test execution completed!'
            }
        }
    }
}
