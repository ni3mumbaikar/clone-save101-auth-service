pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                bat "gradle clean test"
            }
        }
        stage('Build'){
            steps{
                bat "gradle build"
            }
        }
    }
}