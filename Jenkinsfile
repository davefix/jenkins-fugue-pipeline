pipeline {

	agent any

	stages {
        
		stage('Checkout') {
			steps {		
                sh '''
				    echo "Checking out ..."	                											
                    ls -lah
                '''
			}
		}

		stage('Build') {
			steps {
				echo "Building ..."	
			}
		}
	
		stage('Test') {
			steps {
				echo "Testing ..."	
			}
		}

		stage('Deploy') {
			steps {
				echo "Deploying ..."	
			}
		}	

	} 
}
