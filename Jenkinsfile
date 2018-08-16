pipeline{
    agent { docker {images 'node:6.3' } }
    stages {
        stage('build') {
            steps{
                sh 'npm --version'
            }
        }
    }
}