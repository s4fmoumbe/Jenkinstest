pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build'){
            steps {
                sh '''
                ls
                pwd
                uname
                touch franck
                '''
            }
        }
    }
}
