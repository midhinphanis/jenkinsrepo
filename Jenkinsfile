pipeline {
    agent any 

    environment {
        sport = "cricket"
        name = "rohit"
    }

    stages {

        stage("first stage") {
            environment {
                sport = "soccer"
            }
            steps {
                echo "the sport is ${sport}"
                echo "the player is ${name}"
            }
        }

        stage("second stage") {
            steps {
                echo "the sport is ${sport}"
                echo "the player is ${name}"
            }
        }

    }
}
