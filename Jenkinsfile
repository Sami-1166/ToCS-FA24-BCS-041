pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac square.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Square'
            }
        }
    }
}
