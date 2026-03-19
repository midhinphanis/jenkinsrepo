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
        stage('second stage'){
             when{
                allOf{
                    branch 'feature-branch'
                    environment name: 'team' , value: 'india'
                }
             }
        steps{
            echo "team is india"
        }
    }
}
}
