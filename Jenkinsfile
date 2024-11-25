pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'javac AddTwoNumbers.java' // Compiles your Java code
            }
        }
        stage('Test') {
            steps {
                sh 'java AddTwoNumbers' // Runs your Java program
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment stage (placeholder)'
                // Add real deployment steps here
            }
        }
    }
}
