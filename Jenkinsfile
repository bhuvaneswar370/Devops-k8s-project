pipeline {
    agent any
	tools {
		mvn '3.6.9'
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
