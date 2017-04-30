pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                sh 'echo $PATH; /Applications/Docker.app/Contents/Resources/bin/docker'
            }
        }
    }
}
