pipeline {
	agent any
	stages {
		stage ('Git checkout') {
			steps {
				echo 'This is GIT checkout stage'
			}
		}
		stage ('Build') {
			steps {
				echo 'This is a build stage'
			}
		}
		stage ('Push to artifactory') {
			steps {
				echo 'this is push stage'
			}
		}
		stage ('Deploy') {
			steps {
				echo ' this is deploy stage'
			}
		}
	}
}
