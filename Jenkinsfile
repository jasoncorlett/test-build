pipeline {
    agent any
    
    environment {
        VERSION = 2
    }
    
    stages {
        stage("Build") {
            steps {
                sh "echo Version $VERSION"
                sh "date"
                sh "env"
            }
        }
    }
}
            
