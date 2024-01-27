pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Branch Name: ${env.BRANCH_NAME}"
                echo "Change ID: ${env.CHANGE_ID}"
            }
        }
    }
}
