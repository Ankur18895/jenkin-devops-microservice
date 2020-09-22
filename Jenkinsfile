
//Declarative
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"

			}
		}
		stage('Test') {
			steps {
				
				echo "Test"
				
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration test"
			}
		}
	} 
	post{
		always{
			echo 'I am awesome'
		}
		sucess{
			echo 'I run when Sucess'
		}
		failure{
			echo 'I run when failure'
		}
	}
}