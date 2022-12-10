pipeline {
    agent any

    environment {
        ENV_URL = "pipeline.jenkins.io"
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage ("shell") {
            steps{
                sh "echo hai"
                sh "This is sample URL : $ENV_URL"
            }
        }

 
       
    }
}
