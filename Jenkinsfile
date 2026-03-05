pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/VementerOp/Jenkins.git'
            }
        }
        stage('compiling') {
            steps {
                bat 'javac domain.java'
            }
        }
        stage('execting') {
            steps {
                bat 'java domain'
            }
        }
    }
}
