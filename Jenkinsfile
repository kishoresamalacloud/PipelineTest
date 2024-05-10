pipeline {
    agent any
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage ('Deployed to PRODUCTION'){
            when {
                allOf {
                    branch 'production'
                    environment name: 'DEPLOY_TO', value: 'production'
                }
            }
            steps {
                echo "NOT Deployed to PRODUCTIO"
            }
        }
        stage ('This is alternative stage'){
            steps {
                echo 'Not Deployed to PRODUCTION'
            }
        }
    }
}
