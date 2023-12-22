pipeline {
    agent any
	tools {
		maven '3.9.6'
	}
    environment {
      PATH =   "C:\Program Files\Maven\apache-maven-3.9.6\bin\L$PATH"
    }
    stages {
        stage('Build the source code using maven') {
            steps {
                mvn clean package
            }
        }
		
		stage('stage2') {
            steps {
                echo 'Hello World'
            }
        }
		
		stage('stage3') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
