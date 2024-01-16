pipeline {
    agent any
   
    stages{
        stage('build docker backend'){
            step {
                echo 'build docker api'
                sh 'cd api'
                sh 'npm run build'
            }
        }
       
    }
}