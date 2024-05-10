pipeline {
    agent any
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage ('This is allOff condition'){
            when {
                allOf {
                    branch 'production'
                    environment name: 'DEPLOY_TO', value: 'production'
                }
            }
            steps {
                echo "Successfully deployed to PRODUCTION"
            }
        }
        stage ('This is alternative stage'){
            steps {
                echo 'Not Deployed to PRODUCTION'
            }
        }
    }
}
