pipeline {

   // agent any

        pipeline {
    agent {
        docker {
            image 'maven:3.6.3'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean install'
				echo "Build"
            }
        }
    }
}
					
					
			  }             
				}
			stage('Test') {
					steps {
							echo "Test"
						

					}  

				}           
	        
			stage('Integration Test') {
				steps {
						echo "Integration Test"

				}             
				
			}

		}

	} 
		

		