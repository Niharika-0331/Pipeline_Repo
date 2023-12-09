@Library('Pipeline_Repo') _
pipeline{
    agent any
	tools{
		gradle('8.3')
	}
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
	     stage('Build') {
            steps {
                script {
                    // Run Gradle build command
                    sh 'gradle clean'
                }
            }
        }
    }
}
	
	 

