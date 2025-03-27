pipeline {
    agent { docker { image 'node:22.14.0-alpine3.21' } }
    stages {
        stage('Show Node Version') {
            steps {
                sh 'node --version'
            }
        }
        stage('Hello Stage') {
            steps {
                sh 'echo Hello from Jenkins!'
            }
        }
    }
}
