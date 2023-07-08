pipeline {
    agent any

    stages {
        stage("folder") {
            steps {
                sh "pwd"
            }
        }
        stage('Test') {
            steps {
                sh "gradle clean test"
            }
        }
        stage('Build'){
            steps{
                sh "gradle build"
            }
        }
    }
}