//SCRIPTED
//Declarative
pipeline {
	agent any
	stages {
		stage('Build'){
			steps{
				echo "Build"
			}
		}
		stage('Test'){
			steps{
				echo "Test"
			}
		}
		stage('Integration Test'){
			steps{
				echo "Integration Test"
			}
		}
	}
	post {
		always {
			echo 'Im awesome. I run alwaysss'
		}
		success {
			echo 'I run when you are succesful'
		}
		failure {
			echo 'I run when you fail'
		}
	}
	
}
