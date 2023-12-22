pipeline {
    agent any
	stages {
        stage('Build the source code using maven') {
            steps {
                bat "mvn clean package"
            }
        }
	}
}
