pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                    sh "aws cloudformation create-stack \--stack-name myteststack \ --template-body file://S3bucket.json --region 'us-east1' "
                }
            }
        }
    }
}
