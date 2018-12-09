pipeline{
	agent{
		docker 
		     { 
			     image 'node:7-alpine' 
			     registryUrl 'https://registry.hub.docker.com'
		     }
	     }
	stages{
		stage('Test'){
				steps{
					sh  'node --version'
			    		 }
			}
		}
	}	
