pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh './mvnw --version'
                sh './mvnw build'
            }
        }
    }
}
