pipeline {
	agent any
	stages {
		stage('Building main stage') {
			when {
				branch 'main'
			}
			steps {
				echo "Building main"
			}
		}
		
		stage('Building dev stage') {
			when {
				branch 'dev'
			}
			steps {
				echo "Building dev"
			}
		}
	}
}
