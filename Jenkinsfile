pipeline {
    agent any
    tools {
        maven 'anrem local maven isntallation'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                sh 'java -cp target/myproject-1.0-SNAPSHOT.jar com.example.HelloWorld'
            }
        }
    }
}

