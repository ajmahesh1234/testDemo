pipeline {
    agent any
    stages {
        stage('build Stage') {
            steps {
               withMaven(maven : 'Maven' ){
                bat 'mvn clean'
	       }
		
                
            }
        }
		
	//	stage('Testing Stage') {
          //  steps {
            //   withMaven(maven : 'Maven' ){
              //  bat 'mvn test'
	       //}	       
                
            //}
        //}
	stage('Deploy Stage') {
            steps {
               withMaven(maven : 'Maven' ){
                bat 'mvn deploy'
	       }
                
            }
        }	
		
    }
}
