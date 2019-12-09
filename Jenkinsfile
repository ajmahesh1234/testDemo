pipeline {
    agent any
    stages {
        stage('build Stage') {
            steps {
               withMaven(maven : 'Maven' ){
                bat 'mvn clean build'
	       }
		
                
            }
        }
		
		stage('Testing Stage') {
            steps {
               withMaven(maven : 'Maven' ){
                bat 'mvn test'
	       }	       
                
            }
        }
		
		
    }
}
