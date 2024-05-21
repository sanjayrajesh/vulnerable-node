pipeline {
    options {
        buildDiscarder(logRotator(numToKeepStr: "10"))
    }
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}