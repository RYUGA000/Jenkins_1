pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/RYUGA000/Jenkins_1.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building step"'
            }
        }

        stage('Test') {
            steps {
                sh 'python hello_world.py'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deployment step"'
            }
        }
    }
}
