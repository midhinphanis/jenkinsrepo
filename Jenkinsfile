pipeline {
    agent any

    environment {
        sport = "cricket"
        name = "rohit"
    }

    stages {
        stage ("build") {
            environment {
                game = "soccer"
            }

            steps {
                echo "enjoy playing ${sport}"
                echo "batsmen is ${name}"
                echo "another play is ${game}"
            }
        }
    }
}
