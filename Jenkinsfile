pipeline {
    agent any

    stages {
        stage('Test Credentials') {
            environment {
               GITHUB_CREDS = credentials('midhinphanis_github_creds')
            }
            steps {
                 echo "GITHUB_CREDS credentials is ${ GITHUB_CREDS}"
                echo "Username is ${GITHUB_CREDS_USR}"
                echo "Password is ${GITHUB_CREDS_PSW}"
            }
        }
    }
}
