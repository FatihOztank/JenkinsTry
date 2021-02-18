//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                //sh 'sudo usermod -a -G docker jenkins'
            }
        }
    }
}
