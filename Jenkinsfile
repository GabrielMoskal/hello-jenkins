/* Requires the Docker Pipeline plugin  test2*/
pipeline {
    agent {
        docker {
            image 'maven:3.9.0-eclipse-temurin-11'
            args '-v C:\\Users\\Gabriel\\.jenkins:\\workspace -v ${WORKSPACE}:\\app'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'java --version'
            }
        }
    }
}