pipeline {
    agent any
    stages {
        stage('Fetch from GitHub') {
            steps {
                git 'https://github.com/Varunkaushik2004/DEVOPS.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Build Step"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing Step"'
            }
        }
    }
}