pipeline {
	agent any
		stages {
			stage ('one') {
				steps {
					echo "hello, this pradeep from stage one"
				}
			}
			
			stage ('two') {
				steps {
					input('do you wanr=t to proceed')
				}
			}
			
			stage ('three') {
				when {	
					not {
						branch "master"
					}
				}
				steps {
					echo "hello from stage 4"
				}
			}			 
	}
}
			
