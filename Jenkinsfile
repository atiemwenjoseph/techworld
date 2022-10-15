pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
            echo 'Building the application'
            }
        }
         stage('Test') {
            steps {
            echo 'Testing the application'
            }
        }
         stage('Deploy') {
            steps {
            echo 'Deploying the application'
            }
        }
         stage('Creating files') {
            steps {
                sh 'mkdir Jenkins-test'
                sh 'cd Jenkins-test'
                sh 'echo 'Deploying the application' >> file.txt'
            }
        }
         stage('Monitor') {
            steps {
                sh 'ls -al'
            }
        }
    }
}
