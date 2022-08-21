pipeline {
    agent any

    stages {
        stage('Pull') {
            steps {
                git url: 'https://https://github.com/thihathura/workhook-jenkins-test/edit/main/Jenkinsfile' , branch: 'main'
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
