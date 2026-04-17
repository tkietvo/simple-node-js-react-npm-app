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
			    cd 'jenkins/scripts'
                bat 'test.sh'
            }
        }
    }
}