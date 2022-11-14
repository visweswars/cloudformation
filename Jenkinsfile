pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'arn:aws:cloudformation:us-east-1:302019044897:stack/myfirst-web-application/7833a250-6404-11ed-9cf4-122daf2fc495'
            }
        }
        stage('Test') { 
            steps {
                sh'test the code'
            }
        }
        stage('Deploy') { 
            steps {
                sh'deploy the code'
            }
        }
    }
}
