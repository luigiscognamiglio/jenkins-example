
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.8.6-openjdk-11-slim' } }
    stages {
        stage('stage1') {
            steps {
                echo "Hello World!"
            }
        }
        stage('stage2') {
            steps {
                echo "Hello World!"
            }
        }
    }
}
