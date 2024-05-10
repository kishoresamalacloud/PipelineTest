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
                echo "NOT Deployed to PRODUCTION"
            }
        }
        stage ('NOT Deployed to PRODUCTION'){
            steps {
                echo 'Not Deployed to PRODUCTION'
            }
        }
    }
}
