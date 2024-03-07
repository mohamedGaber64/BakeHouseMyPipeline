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
