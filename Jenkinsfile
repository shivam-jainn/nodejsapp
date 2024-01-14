pipeline{
    agent{
        docker{
            image 'node:20.10.0-alpine3.19' 
            args '-p 3000:3000'
        }
    }
    stages{
        stage('build'){
            steps{
                sh 'npm install'
            }
        }
    }
}