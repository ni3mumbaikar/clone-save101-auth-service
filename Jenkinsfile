pipeline {
    agent any

    stages {
        dir("folder") {
            sh "pwd"
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