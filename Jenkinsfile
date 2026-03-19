pipeline{
    agent any
    environment{
        match = "cricket"
        team = "india"
    }
    stages {
        stage('first stage'){
            when{
                anyOf{
                    branch 'main'
                    environment name: 'match' , value: 'cricket'

                }
                
            }
            steps{
                echo "india playing cricket"
            }
        }
    }
}

