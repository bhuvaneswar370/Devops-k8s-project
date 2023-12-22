pipeline {
    agent any
	stages {
        stage('Build the source code using maven') {
            steps {
                bat 'mvn clean install'
		    //after setting maven path need to restart the instance
            }
        }
	}
}
