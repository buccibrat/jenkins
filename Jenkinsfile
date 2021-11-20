pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'su benjo'
                sh 'sifra'
                sh 'sudo apt install build-essential'
                sh 'gcc -o main main.c'
                sh './main'
            }
        }
    }
}
