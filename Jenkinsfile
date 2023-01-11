@Library('jenkins-libraries@dev')_

pipeline {

	agent any

	stages {
        
		stage('Checkout') {
			steps {		
                sh '''
				    echo "Checking out ...."	                											
                    ls -lah
                '''
			}
		}

		stage('Build') {
			steps {
				echo "Building ...."	
     			fugueScan ('jenkins-fugue-pipeline', 'dev')				
			}
		}
	} 
}
