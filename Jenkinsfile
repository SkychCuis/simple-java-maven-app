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
                ls -lh
            }
        }
    }
}
