pipeline {
    agent any
    options {

    }
    stages{
        stage('build docker backend'){
            step {
                sh 'cd api'
                sh 'docker compose up --build'
            }
        }
        stage('build doker client'){
            step {
             step {
                sh 'cd ../client'
                sh 'docker compose up --build'
            }   
            }
        }
    }
}