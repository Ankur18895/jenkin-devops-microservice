
//Declarative
pipeline {
	agent any
	//agent { docker { image 'maven:3.6.3'} } 
	stages {
		stage('Build') {
			steps {
				sh "mvn--version"
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
		success{
			echo 'I run when Sucess'
		}
		failure{
			echo 'I run when failure'
		}
	}
}