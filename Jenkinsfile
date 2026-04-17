pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                bat 'npm install' 
            }
        }
		stage('Test') {
            steps {
			    powershell 'jenkins/scripts/test.sh'
            }
        }
    }
}