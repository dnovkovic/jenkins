pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..';
                cat Jenkinsfile | grep 'Build'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}