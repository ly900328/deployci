// Jenkinsfile (Scripted Pipeline)
/* 需要Docker Pipeline插件 */
node('docker-1') {
    checkout scm
    stage('Build') {
        docker.image('jenkins/slave:latest').inside {
            sh 'python --version'
        }
    }
}