pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // You can add your build commands here, e.g., Maven, Gradle, etc.
                // sh 'mvn clean install' (for a Maven project)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here, e.g., unit tests, integration tests, etc.
                // sh 'mvn test' (for a Maven project)
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
