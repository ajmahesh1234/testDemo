pipeline {
    agent any
    stages {
        stage('build Stage') {
            steps {
                withMaven(maven : 'apache-maven-3.3.9') {
                bat 'mvn clean compile'
		}
                
            }
        }
		
		stage('Testing Stage') {
            steps {
               
                bat 'mvn test'
                
            }
        }
		
		stage('Deploy Stage') {
            steps {
               
                bat 'mvn deploy'
                
            }
        }
    }
}
