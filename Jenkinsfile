pipeline{

	agent any

	environment {
		DOCKERHUB_CREDENTIALS=credentials('docker')
	}

	stages {
	    
	    stage('gitclone') {

			steps {
				git 'https://github.com/ramdisk-ott/Helloword.git'
			}
		}
	}
 

}
