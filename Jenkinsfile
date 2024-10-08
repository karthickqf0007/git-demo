pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
    t)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'

            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
