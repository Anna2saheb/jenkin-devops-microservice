pipeline{
 agent {docker {image 'maven:3.6.3'}}
	stages{
		stage('Build') {
			step{
				echo 'mvn --version'
				echo "Build"
			}
		}	
		stage('Test') {
			step{
				echo "Test"
			}
		}
		stage('Integration Test') {
			step{
				echo "Integration Test"
			}
		}
	}
}	
