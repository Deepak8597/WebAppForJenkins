pipeline {
    agent any
    tools {
        Maven "3.8.7"
    }
    stages {
        stage('Clean and Install') {
            steps {
               bat 'mvn clean install'
            }
        }
        stage('Package') {
            steps {
               bat 'mvn package'
            }
        } 
    }
}
