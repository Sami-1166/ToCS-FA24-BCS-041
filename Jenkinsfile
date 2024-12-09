pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac Square.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Square'
            }
        }
    }
}
