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
	post{
		always{
			echo 'I always run'
		}
		success{
			echo 'only run if success'
		}
		failure{
			echo 'run in case of failure'
		}
	}
}
