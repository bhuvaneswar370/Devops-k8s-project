pipeline {
    agent any
	
        stage('Build the source code using maven') {
            steps {
                bat "mvn clean package"
            }
        }
}
