pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name S3Encryption --template-body file://template.yml --region 'us-east-1'"
              }
             }
            }
            }