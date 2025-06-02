pipeline {
    agent any

    stages {
        stage('Pull from GitHub') {
            steps {
                git branch: 'main', url: 'https://github.com/Malaikakhattak69/Devops.git'
            }
        }

        stage('Build') {
            steps {
                bat 'echo ===== BUILD STAGE ====='
                bat 'type index.txt'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo ===== DEPLOY STAGE ====='
                bat 'type index.html'
            }
        }
    }
}
