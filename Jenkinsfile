pipeline {
    agent any
    tools{
        nodejs "my-nodejs"
    }
    stages{
        stage('build app backend'){
            steps {
                echo 'build app api'
                sh 'cp ./api/example.env ./api/.env'
                sh 'yarn --cwd ./api/ install'
                sh 'yarn --cwd ./api/ run build'
            }
        }
       
    }
}