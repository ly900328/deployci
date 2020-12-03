// Jenkinsfile (Declarative Pipeline)
/* 需要Docker Pipeline插件 */
pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}