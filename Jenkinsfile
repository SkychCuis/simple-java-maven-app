pipeline {
    agent {
        docker {
            image 'maven:3.9.3-eclipse-temurin-17'
        }
    }
    stages {
        stage('Build') {
            steps {
                echo "Build Stage Test 2"
                sh "mvn --version"
                sh "mvn clean package"
                sh "ls -lh"
                sh "docker ps "
                sh "docker image list"
                sh "pwd"
            }
        }
    }
}
