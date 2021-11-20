pipeline {
    agent { docker { image 'gcc' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "hello world"'
            }
        }
    }
}
