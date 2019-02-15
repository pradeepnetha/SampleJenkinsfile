pipeline {
	agent any 
		stages {
		      	stage('one') {
				steps {	
				echo "hello from jenkinsfile 1"
				}	
			}
			stage('two') {
				steps {
					input ('doyou wany to procees')
				}
			}
			stage('three') {
				when {
					not {
						branch "feature"
					}
				}
				steps {
					echo "hello from stage 4"
				}
			}
		}
	
}
