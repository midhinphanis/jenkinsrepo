pipeline {
    agent any

    environment {
        match = "cricket"
        team = "india"
    }

    stages {
        stage('first stage') {
            when {
                not {
                    environment name: 'match', value: 'soccer'
                }
            }
            steps {
                echo "india playing cricket"
            }
        }

        stage('second stage') {
            when {
                expression { BRANCH_NAME == 'main' }
            }
            steps {
                echo "team is india"
            }
        }
    }
}
