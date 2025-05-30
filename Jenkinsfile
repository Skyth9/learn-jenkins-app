pipeline {
    agent any

    stages {
        stage('Build') {
            
            steps {
                sh '''
                    pwd
                    ls -la
                    node --version
                    npm --version
                    npm run build
                    ls -la
                '''
            }
        }
    }
}