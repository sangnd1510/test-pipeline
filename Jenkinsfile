pipeline {
    agent any
   tools{
       node "my-nodejs"
   }
    stages{
        stage('build docker backend'){
            steps {
                echo 'build docker api'
                sh 'cd api'
                sh 'node --version'
            }
        }
       
    }
}