pipeline {
    agent any
	tools {
		maven "MAVEN_HOME"
	}
    stages {
        stage('Git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/GoraDivya/newrepoistry.git'
            }
        }
		stage('UNIT testing') {
			steps {
				sh 'mvn test'
			}
		}
    }
}
