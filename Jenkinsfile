pipeline {
    agent any 
    environment {
        name = "kishore"
        course = "k8s"
    }
    stages {
        stage ('This is Credentials-Test') {
            environment {
                GITHUB_CREDS = credentials('Git-Creds-New')
            }
            steps {
                echo "GitHub Credentials are ${GITHUB_CREDS}"
                echo "UserId is ${GITHUB_CREDS_USR}"
                echo "Password Is ${HITHUB_CREDS_PSW}"
            }
        }
    }
}
