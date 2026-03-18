pipeline {
    agent any

    environment {
        match = "cricket"
        team = "india"
    }

    stages {
        stage('first stage') {
            when {
                environment name: 'match', value: 'cricket'
            }
            steps {
                echo "india playing cricket"
            }
        }
    }
}
