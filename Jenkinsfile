pipeline {
	agent { docker 'myjenkinsdocker:2' }
	stages {
		stage('build') {
			steps {
				sh 'npm start'
			}
		}
	}
}
