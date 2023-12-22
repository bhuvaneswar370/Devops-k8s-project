pipeline {
    agent any
	tools { 
	stages {
        stage('Build the source code using maven') {
            steps {
                bat 'mvn clean install'
            }
        }
	}
}
