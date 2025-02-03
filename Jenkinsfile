pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                bat '''
                    node --version
                    npm start
                '''
            }
        }
    }
}
