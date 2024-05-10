pipeline {
    agent any
    environment {
        DEPLOY_TO = "prodcution"
    }
    stages {
        stage ('This is WHEN-NOT_condition') {
            when {
                not {
                    equals expected: "production", actual: "${DEPLOY_TO}"
                }
            }
            steps {
                echo "successfully NOT CONDITION is Processed"
            }
        }
    }
}
