pipeline {
    agent any
    stages {
        stage('build Stage') {
            steps {
               
                bat 'mvn clean'
		
                
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
