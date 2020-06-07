pipeline {
    agent any 
    stages {
        stage('---Clean Karo---') { 
            steps {
                sh "mvn clean" 
            }
        }
        stage('---Test Apo---') { 
            steps {
                sh "mvn test" 
            }
        }
        stage('--Package--') { 
            steps {
                sh "mvn package"
            }
        }
    }
}