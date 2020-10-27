pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build'
            }
        }

        stage('Test') {
            steps {
                echo 'Test'
            }
        }

        stage('Integrarion Test') {
            steps {
                echo 'Integration Test'
            }
        }
    }

    post {
        always {
            echo 'Im awesome. I run always'
        }
        success {
            echo 'I run when you re succeful'
        }
        success {
            echo 'I run when you fail'
        }
    }
}
