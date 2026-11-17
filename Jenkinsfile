pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'GitHub source code checked out successfully!'
            }
        }

        stage('Test Website') {
            steps {
                sh 'test -f index.html'
                echo 'Website file found successfully!'
            }
        }

        stage('Pipeline Success') {
            steps {
                echo 'My Simple Website Pipeline Completed Successfully!'
            }
        }
    }
}
