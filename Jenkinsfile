pipeline {
    agent any
    stages {
        stage('build Stage') {
            steps {
                withMaven(maven : 'apache-maven-3.3.9' ){
                sh 'mvn -B -DskipTests clean'
                }
            }
        }	
		
		
        }
    }
