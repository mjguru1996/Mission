pipeline{
    agent any
    tools{
        maven 'maven 3.9.2'
        jdk 'jdk 21'
    }
    stages{
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}