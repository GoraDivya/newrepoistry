pipeline {
    agent any 
    stages {
        stage ('check out') {
            steps {
                git branch :'main', url: 'https://github.com/GoraDivya/jenkins.repo'
            }
        }
    }       
}
