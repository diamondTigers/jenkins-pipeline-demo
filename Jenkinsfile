pipeline {
    agent any

    stages {
        stage('Pull') {
            steps {
                echo 'Cloning from GitHub...'
                bat 'dir'
            }
        }

        stage('Build') {
            steps {
                echo 'Running build steps...'
                bat 'echo Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo All tests passed!'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                bat 'echo Deploy done!'
            }
        }
    }
}
