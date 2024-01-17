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
                sh 'npm install --prefix ./api/'
                sh 'npm run build --prefix ./api/'
            }
        }
       
    }
}