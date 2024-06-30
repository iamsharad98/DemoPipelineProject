pipeline {
    agent {
        label 'agentlinux'
    }
    stages {
        stage('Check Version') {
            steps {
                sh "node --version"
                sh "npm --version"
            }
        }
        // Add more stages as needed
    }
    // Post-build actions, notifications, etc.
}
