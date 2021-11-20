pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'sudo apt install build-essential'
                sh 'gcc -o main main.c'
                sh './main'
            }
        }
    }
}
