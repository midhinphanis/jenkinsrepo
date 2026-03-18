pipeline {
    agent any 

    environment {
        MUMBAI_CREDS = credentials('rohit_mumbai_creds')
        CSK_CREDS = credentials('csk_creds')
    }

    stages {
        stage('Test Credentials') {
            steps {
                echo "MUMBAI_CREDS credentials is ${MUMBAI_CREDS}"
                echo "Username is ${MUMBAI_CREDS_USR}"
                echo "Password is ${MUMBAI_CREDS_PSW}"
            }
        }
    }
}
