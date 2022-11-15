pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                    sh "export AWS_DEFAULT_REGION=us-east-1"
                    sh "aws cloudformation create-stack --stack-name mysecond-web-application --template-body file:///tmp/cfn/ec2.yaml "
                }
            }
        }
    }
}
