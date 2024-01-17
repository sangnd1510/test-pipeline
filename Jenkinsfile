pipeline {
    agent any
    tools{
        nodejs "my-nodejs"
    }
    stages{
        stage('build app backend'){
            steps {
                echo 'build docker api'
                sh 'cd api'
                sh 'npm run build'
            }
        }
       
    }
}