pipeline {
    agent any
    stages {
        stage('build Stage') {
            steps {
                
                bat 'mvn clean compile'
                
            }
        }
		
		stage('Testing Stage') {
            steps {
               
                sh 'mvn test'
                
            }
        }
		
		stage('Deploy Stage') {
            steps {
               
                sh 'mvn deploy'
                
            }
        }
    }
}
