pipeline{
    agent any 
    stages {
        stage('Test Credentials'){
    environment{
        MUMBAI_CREDS = credentials('rohit_mumbai_creds')
    }
        }
    }
     
    steps{
        echo = "MUMBAI_CREDS credentials is ${MUMBAI_CREDS}"
        echo = "Username is ${MUMBAI_CREDS_USR}"
        echo = "Password is ${MUMBAI_CREDS_PSW}"
    }
    
}
