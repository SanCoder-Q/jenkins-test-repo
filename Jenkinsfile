pipeline {
    agent { docker 'node:6' }
    stages {
        stage('build') {
            steps {
                sh 'npm start'
            }
        }
    }
}
