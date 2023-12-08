@Library('Pipeline_Repo') _
pipeline{
    agent any
    stages {
      stage('Git Checkout') {
        steps {
         script{
            checkout_script(params)
            }
       }
     }
    }
}
	
	 

