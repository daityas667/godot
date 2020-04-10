pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'scons platform=linux'
            }
        }
    }
}
