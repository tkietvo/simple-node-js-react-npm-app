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
			    dir 'jenkins/scripts'
                bat 'test.sh'
            }
        }
    }
}