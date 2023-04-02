/* Requires the Docker Pipeline plugin  test2*/
pipeline {
    agent {
        docker {
            image 'maven:3.9.0-eclipse-temurin-11'
            //args '-v C:\\Users\\Gabriel\\.jenkins:\\workspace -v ${WORKSPACE}:\\app'
            args '-v C:\\Users\\Gabriel\\.m2:/root/.m2 -v C:\\Users\\Gabriel\\workspace\\My-Pipeline_main:/app'
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