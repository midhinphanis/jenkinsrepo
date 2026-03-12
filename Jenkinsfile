pipeline {
    agent { 
        label ('myslave')
    
    }

    stages {

        stage('Hostname') {
            steps {
                sh 'hostname -i'
            }
        }

        stage('Checkout') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }

    }
}
