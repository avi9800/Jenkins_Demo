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
		
		stage('Building sidekick stage') {
			when {
				branch 'sidekick'
			}
			steps {
				echo "Building sidekick"
			}
		}
	}
}
