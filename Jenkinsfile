//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
		sh 'pip3 --version'
		sh 'echo hello, ali'
		sh 'pip3 install tk'

            }
        }
    }
}
