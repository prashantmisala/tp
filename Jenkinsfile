pipeline {
agent { label 'slave'}
   stages {
     stage('validate') {
     steps {
     sh 'mvn validate'
       }
     }
     stage('compile') {
     steps {
     sh 'mvn compile'
	}
     }
     stage('package') {
     steps {
     sh 'mvn package'
       }
     }
    }
 }	
