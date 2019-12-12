pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000' 
        }
    }
    environment {
        PATH = "C:\\Users\\i342835\\.jenkins\\workspace\\simple-node-js-react-npm-app"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}