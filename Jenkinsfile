pipeline {
    agent any

    stages {
        stage('Make Changes') {
            steps {
                script {
                    sh 'echo " one more info" >> README.md'
                }
            }
        }

        stage('git init') {    #gbgbgngbgnhnhbhnhn
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


