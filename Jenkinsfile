pipeline {
    agent any 
    stages {
        stage ('check out') {
            steps {
                git branch :'main', url: 'https://github.com/GoraDivya/newrepoistry/'
            }
        }
        stage ('unit test') {
            steps {
                sh 'mvn test'
            }
    }   }       
}
