pipeline {
    agent any
    environment {
        name = "kishore"
        course = "Devops"
    }
    stages {
        stage ('build') {
            environment {
                cloud = "GCP"
            }
            steps {
                echo "Welcome ${name}"
                echo "You have enrolled for ${course}-course"
                echo "You are certified in ${cloud}-cloud"
            }
        }
    }
