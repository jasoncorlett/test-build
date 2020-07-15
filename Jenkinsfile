pipeline {
    agent any
    
    environment {
        VERSION = 3
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
            
