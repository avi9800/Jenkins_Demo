pipeline {
	agent any
	stages {
		stage('Building stage') {
			when {
				branch 'main'
			}
			steps {
				echo "Building main"
			}
		}
		
		stage('Building stage') {
			when {
				branch 'sidekick'
			}
			steps {
				echo "Building sidekick"
			}
		}
	}
}
