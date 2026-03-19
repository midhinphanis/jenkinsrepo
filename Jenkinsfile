pipeline {
    agent any

    stages {
        stage('Test Credentials') {
            environment {
                MUMBAI_CREDS = credentials('rohit_mumbai_creds')
            }
            steps {
                echo "Username is ${MUMBAI_CREDS_USR}"
                echo "Credentials loaded successfully"
            }
        }
    }
}
