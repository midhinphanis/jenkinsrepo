pipeline{
    agent any
    environment{
        match = "cricket"
        team = "india"
    }
    stages {
        stage('first stage'){
            when{
                allOf{
                    branch 'feature-branch'
                    environment name: 'match' , value: 'cricket'

                }
                
            }
            steps{
                echo "india playing cricket"
            }
        }
    }
}

