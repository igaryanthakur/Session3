pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git "https://github.com/igaryanthakur/Session3.git"
            }
        }
        stage('Build') {
            steps {
                bat "javac Test.java"
            }
        }
        stage('Execute') {
            steps {
                bat "java Test"
            }
        }
    }
}
