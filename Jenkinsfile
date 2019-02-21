pipeline {
	agent any 
		stages {
			stage ('build') {
				steps {
				   step {
					git credentialsId: 'github', url: 'https://github.com/pradeepnetha/SampleJenkinsfile'
					sh 'mvn --verion'
				}
			}
		}
	}
