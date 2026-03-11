pipeline {
    agent { 
      label('myslave')
    }

    stages {
       stage('hostname') {
            steps {
                echo 'hostname -i'
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

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
