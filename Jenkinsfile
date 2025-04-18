pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              echo"build"
            }
        }
        stage('Test') {
            steps {
                 echo"test"
                sh'''
                python hello.py '''
            }
        }
        stage('Deploy') {
            steps {
                 echo"deploy"
            }
        }
    }
}
