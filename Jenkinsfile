pipeline {
    agent any
    environment {
        name = "kishore"
        course = "Devops"
        cloud = "AWS"
    }
    stages {
        stage ('Output will be pavan - devops - gcp') {
            environment {
                cloud = "GCP"
            }
            steps {
                echo "Welcome ${name}"
                echo "You have enrolled for ${course}-course"
                echo "You are certified in ${cloud}-cloud"
            }
        }
        stage ('Output will be pavan - cloud - azure') {
            environment {
                name = "pavan"
                course = "CLOUD"
                cloud = "Azure"
            }
            steps {
                echo "Welcome ${name}"
                echo "You have enrolled for ${course}-course"
                echo "You are certified in ${cloud}-cloud"              
            }
        }
    }
}
