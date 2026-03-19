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
                    environment name: 'game' , value: 'soccer'
                }
                
            }
            steps{
                echo "india playing soccer"
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
