pipeline {
    agent any

    stages {
        stage('Make Changes') {
            steps {
                script {
                    sh 'echo " one more info" >> Jenkinsfile'
                }
            }
        }

        stage('git init') {   
            steps {
                sh 'git init'
            }
        }
        
        stage('git add') {
            steps {
                sh 'git add .'
            }
        }

        stage('git commit') {
            steps {
                sh 'git commit -m "updates"'
            }
        }
    }
}


