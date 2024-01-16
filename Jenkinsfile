pipeline {
    agent any
    options {

    }
    stages{
        stage('build docker backend'){
            step {
                echo 'build docker api'
                sh 'cd api'
                sh 'docker compose up --build'
            }
        }
       
    }
}