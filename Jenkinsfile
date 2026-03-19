pipeline{
    agent any
    environment{
        match = "cricket"
        team = "india"
    }
    stages {
        stage('first stage'){
            when{
                not{
                    branch 'main'

                }
                
            }
            steps{
                echo "india playing cricket"
            }
        }
        stage('second stage'){
             when{
                allOf{
                    branch 'main'
                    environment name: 'team' , value: 'india'
                }
             }
        steps{
            echo "team is india"
        }
    }
}
}
