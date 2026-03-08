pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/VementerOp/Jenkins.git'
            }
        }
        stage('Build') {
            steps {
                bat 'javac jen2.java'
            }
        }
        stage('executing') {
            steps {
                bat 'java jen2'
            }
        }
    }
}
