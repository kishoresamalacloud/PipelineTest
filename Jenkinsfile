pipeline {
    agent any
    stages{
        stage ('THis is branch example') {
            when {
                expression {
                    BRANCH_NAME ==~ /(production|staging)/
                }
            }
            steps {
                echo "production deployment is successfull"
            }
        }
    }
}
