@Library('Pipeline_Repo') _
pipeline{
    agent any
parameters{
        string(name :'branch', defaultValue: 'main')
	    string(name :'url', defaultValue: 'https://github.com/Niharika-0331/Pipeline_Repo.git')
	}
    stages {
      stage('Git Checkout') {
        steps {
         script{
            Checkout_script(params)
            }
       }
     }
	   
    }
}
	
	 

