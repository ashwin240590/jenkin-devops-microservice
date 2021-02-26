// DECLARATIVE
pipeline{
	agent any
	stages{
		stage('Build') {
			steps{
				echo "Build"
				
			}
		}
		stage('Test') {
			steps{
				echo "Test"
			}
		}
		stage('Intigration Test') {
			steps{
				echo "Intigration Test"
			}
		}
	} 
	
	post {
		always{
			echo 'I m awesome, I run always'
		}
		success{
			echo 'I run when you r successful'
		}
		failure{
			echo ' I run when you fail'
		}
	}
}

//SCRIPTED

// node {
//	stage('Build') {
//		echo "Build"
//	}
//	stage('Test') {
//		echo "Test"
//	}
//	stage('Intigration Test') {
//		echo "Test"
//	}
//}
