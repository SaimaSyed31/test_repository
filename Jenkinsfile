pipeline{
	agent any
		stages{
			stage('One'){
				steps{
					echo "Hi, this is a pipeline test"
				}
			}
			stage('Two'){
				steps{
					input('Do you want to proceed?')
				}
			}
			stage('Three'){
				steps{
					echo "Bye, we are done!"
				}
			}
		}
	
}
