//SCRIPTED
//Declarative
pipeline {
	agent { docker : { image 'maven:3.6.3'}}
	stages {
		stage('Build'){
			steps{
				sh 'mvn --version'
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
