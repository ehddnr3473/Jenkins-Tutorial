pipeline {
	agent any
	
	stages {
		stage('build') {
			steps {
				echo '빌드 중'
				sh './gradlew build'
			}
		}
	}
}

