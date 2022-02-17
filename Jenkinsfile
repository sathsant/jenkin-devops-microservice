pipeline {
	agent any
	stages {
		stage('Build'){
		steps{
			echo 'build'
			}
		}
		stage('Test'){ 
		steps{
			echo 'Testing'
			}
		}
		stage('Integration test'){
		steps{
			echo 'Integration test'
			}
		}
	}
	post{
		always{
		echo 'I run always'
		}
		success{
		echo 'I run when it is success'
		}
		failure{
		echo 'I run when it is failure'
		}
	}
}
