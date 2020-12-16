// Powered by Infostretch 

timestamps {

node () {

	stage ('flask_python - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '', url: 'https://github.com/ssrful/exercise.python_flask-heroku-deployment.git']]]) 
	}
	stage ('flask_python - Build') {
 			// Shell build step
sh """ 
py web.py 
 """ 
	}
}
}