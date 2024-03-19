pipeline {
    agent any
    
    stages {
        stage('Print Build Number') {
            steps {
                echo "Build Number: ${BUILD_NUMBER}"
            }
        }
        stage('List Files') {
            steps {
                sh 'ls'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building ... slaves'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing ... slaves'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying ... slaves'
            }
        }
    }
}






