pipeline {
    agent any 
    stages {
        stage('Clean') {
            steps {
                bat "gradle clean"
            }
        }
        stage('Build') {
            steps {
                bat "gradle build"
            }
        }
    }
}
