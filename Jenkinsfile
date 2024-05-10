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
                Echo "production deployment is successfull"
            }
        }
    }
}
