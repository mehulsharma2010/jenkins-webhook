pipeline {
    agent any

    stages {
        stage('Stage1') {
            steps {
                echo 'Hello World'
                sh 'printenv'
                sh 'pwd'
            }
        }

        stage('Stage2') {
            steps {
                echo 'Hello World'
                sh 'ls -al'
            }
        }
    }
}
