pipeline {
    agent any
	tools {
		maven
	}
        stages {
        stage('Build the source code using maven') {
            steps {
                bat "mvn clean package"
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
