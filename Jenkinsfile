pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name appachewebserver --template-body file://appacheWebserver.json --region 'us-east-1'"
              }
             }
            }
            }
