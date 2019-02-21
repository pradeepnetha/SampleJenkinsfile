pipeline {
	agent any
		stages {
			stage('one') {
				steps {
					echo "hello form stage1"
				}
			}

			stage('two') {
				steps {
					input "do you want proceed"
					echo "hello from stage two"
				}
			}


			stage('three') {
				
				when {
					not {
						branch 'feature'
					}
				}

				steps {
					echo "hello from 3"
				
				}


			}
		}

}
