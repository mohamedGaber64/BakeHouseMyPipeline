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
                echo 'Building ... Multibranching '
            }
        }
        stage('Test') {
            steps {
                echo 'Testing ... Multibranching '
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying ... Multibranching'
            }
        }
    }
}






