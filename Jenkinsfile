
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Project...'
            }
        }

        stage('Test') {
            steps {
                sh 'test -f index.html && test -f script.js'
                echo 'Tests Passed!'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment Stage Completed!'
            }
        }
    }
}
