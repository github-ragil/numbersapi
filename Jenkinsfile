pipeline{
	agent any
   stages{
	 stage('Checkout Git') { 
		steps {
			checkout scm
			}
			
  }  

	stage('Automation Build, Push & Deploy') {
		steps {
			sh 'sudo bash ./script/script-prod.sh'



  }
  }
  
  }
  }