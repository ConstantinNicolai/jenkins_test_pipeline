pipeline {
    agent any
    tools {
        /usr/share/maven 'Maven3.6.3' // Specify the Maven home directory here
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}

