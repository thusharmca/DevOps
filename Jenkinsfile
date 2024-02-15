pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Process'
            }
        }
        stage('Test') {
            steps {
                echo 'Test Process'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Process'
            }
        }
    }
    post{
        always{
            emailext body: 'test', subject: 'test', to: 'thusharthimmaiah07@gmail.com'
        }
    }
}
