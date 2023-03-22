pipeline {
    agent any
    tools {
        maven 'Maven3.6.3'
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

