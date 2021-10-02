pipeline {
    agent any
    stages {
        stage ("Build") {

            steps {
                echo 'Auto build application'

            }
            
        }

        stage ("Test") {
            steps {
                echo 'testing fhe applicaton'

            }
            
        } 

	    stage ("Building and Publishing Docker Image") {
		    steps {
			    echo 'About to build Docker Image'
		}
        }


        stage ("Deploy to hub") {

            steps {
                echo 'deploying the applicationl to DockerHub'

                }

            }
            
        }
    }