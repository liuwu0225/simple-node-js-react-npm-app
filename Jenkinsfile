pipeline {
    agent {
        docker {
            image 'node:10.17.0' 
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