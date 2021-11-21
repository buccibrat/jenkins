pipeline {
    agent any
    stages {
        stage('build') {
            when {
                branch 'main'
            }
            steps {
                sh 'gcc -o main main.c'
                sh './main'
            }
        }
    }
}
