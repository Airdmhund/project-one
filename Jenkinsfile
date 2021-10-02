pipeline {
    agent any
    stages {
        stage ("Build") {

            steps {
                echo 'Auto build application'
                echo "Buildingfvesion ${NEW_VERSION}"
                echo 'this is forking on new branch'

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
                echo 'deploying the application to DockerHub'

                }

            }
            
        }
    }

    post {
        always {
            echo 'I can see youre working'
        }
    }
