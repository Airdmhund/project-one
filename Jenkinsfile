pipeline {
    agent any
    stages {
        stage ("Build") {

            steps {
                echo 'Auto build application'
                sh 'pwd'

            }
            
        }

        stage ("Test") {
            steps {
                echo 'testing the applicaton'

            }
            
        } 

	    stage ("Building and Publishing Docker Image") {
		    steps {
			    echo 'About to build Docker Image'
		}
        }


        stage ("Deploy to hub") {

            steps {
                echo 'deploying the app to DockerHub'

                }

            }

        stage ("Confirmation") {
            steps {
                echo 'confirmation in test branch'

            }
            
        } 
            
        }
    }
