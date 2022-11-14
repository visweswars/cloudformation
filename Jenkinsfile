pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                    echo 'Hello World'
                    sh 'arn:aws:cloudformation:us-east-1:302019044897:stack/myfirst-web-application/7833a250-6404-11ed-9cf4-122daf2fc495'
                }
            }
        }
    }
}


