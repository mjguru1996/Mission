pipeline{
    agent any
    tools{
        maven 'maven3'
        jdk 'jdk21'
    }
    stages{
        stage('GIT Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/mjguru1996/Mission.git'
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