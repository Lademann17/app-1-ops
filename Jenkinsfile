pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'git@github.com:por314ug/test-repo-2.git', branch: 'main', credentialsId: '1'
            }
        }
    }
}
