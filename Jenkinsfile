pipeline {
	//basic jenkins pipeline script
	agent any
	stages {
		stage ('build') {
			steps {
				echo 'bulding the app...'
				sh 'hostname'
			}
		}
		stage('test') {
			steps {
				echo 'testing the app...'
				sh 'uname -sr'
			}
		}
		stage('deploy') {
			steps {
			echo 'deploying teh app...'
			sh 'uptime'
			}
		}
	}
}
