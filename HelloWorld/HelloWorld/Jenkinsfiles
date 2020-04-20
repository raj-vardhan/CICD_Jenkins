pipeline {
    agent any 
    stages {
        stage('Creating stage') {
            steps {
                test 'mvn clean'
            }
        }
         stage('Testing stage') {
            steps {
                test 'mvn test'
            }
        }
         stage('Packaging stage') {
            steps {
                test 'mvn package'
            }
        }
    }
}
