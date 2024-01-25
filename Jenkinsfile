/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.12.1-alpine3.19' } }
    stages {
        stage('build') {
            steps {
				echo 'Deploy to staging environment'
                /*bat 'python --version'*/
            }
        }
    }
}