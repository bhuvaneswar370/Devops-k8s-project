pipeline {
    agent any
	tools { 
	stages {
        stage('Build the source code using maven') {
            steps {
                mvn clean package
            }
        }
	}
}
