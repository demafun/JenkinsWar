pipeline {
    agent { docker 'maven' }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}

