pipeline {
    agent any

    stages {
        stage('Pull from GitHub') {
            steps {
                git 'https://github.com/Malaikakhattak69/Devops.git'
            }
        }
        stage('Build') {
            steps {
                bat 'echo Simulating build...'
                bat 'type index.txt'
            }
        }
        stage('Deploy') {
            steps {
                bat 'echo Simulating deployment...'
                bat 'type index.html'
            }
        }
    }
}
