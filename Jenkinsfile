node('node'){
	try{
		stage('checkout'){
		checkout scm
		}
	stage('Env setup '){
		env.NODE_ENV="test"
		print "Environment will be : $env.NODE_ENV"
		// bat '' code needs to be completed 
		
		bat "cd C:\Users\SESA528099\PycharmProjects\hope2\venv\Scripts"
		bat "activate"
		bat  "cd C:\Python27"
		bat  "IFE_performance.py"
		
		}		
	}
	catch (err){
		print " Current build is a failure"
		}
		
		

	
}
