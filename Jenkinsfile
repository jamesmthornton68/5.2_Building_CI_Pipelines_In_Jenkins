pipeline {
	agent any
	tools {
    	maven 'maven3.6.3'
	}
	stages {
    	stage("Checkout") {   
        	steps {               	 
            	git url: 'https://github.com/jamesmthornton68/5.2_Building_CI_Pipelines_In_Jenkins.git'          	 
           	 
        	}    
    	}
    	stage('Build') {
        	steps {
        	sh "mvn compile"
			
        	}
    	}
   	 
    	stage("Unit test") {          	 
        	steps {  	 
            	sh "mvn test"          	 
        	}
    	}
	}
<<<<<<< HEAD
}
=======
>>>>>>> fd7126f4d0b25a23dd65dea34a6636e6c7543b8b
