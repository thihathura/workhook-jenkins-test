pipeline {
    agent any

    stages {
        stage('Pull') {
            steps {
                git url: 'https://github.com/thihathura/workhook-jenkins-test.git' , branch: 'main'
            }
        }
        stage('Test') {
            steps {
                sh 'ls -laht'
            }
        }
        stage('Deploy') {
            steps {
                sh 'pwd'
            }
        }
    }
}
