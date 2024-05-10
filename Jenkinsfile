pipeline {
    agent any
    environment {
        name = "kishore"
        course = "Devops"
    }
    stages {
        stage ('this is env example') {
            steps {
               echo "Welcome ${name}"
               echo "You have enrolled for ${course}-course"                
            }
        stage ('This is for predednese') {
            environment {
                cloud = "GCP"
                name = "SAMALA"
            }
            steps {
                echo "Welcome ${name}"
                echo "You have enrolled for ${course}-course"
                echo "you are certified in ${cloud}-cloud"
            }
          }    
        }
    }
}
