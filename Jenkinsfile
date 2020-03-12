//SCRIPTED
//Declarative
pipeline {
	agent { docker { image 'node:13.8'} }
	stages {
		stage('Build'){
			steps{
				sh "node --version"
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
