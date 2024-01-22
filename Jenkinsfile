//Scripted Language
/*node {
	stage('Build') {
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
	stage('Integration Test') {
		echo "Test"
	}
}*/
//Declarative Language

pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
				echo "Build"
			}
		}
	    stage('Unit Test'){
			steps{
				echo "Test"
			}
		}
		stage('Integration Test'){
			steps{
				echo "Integrated"
			}
		}
	}
}
