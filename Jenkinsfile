pipeline {
    agent any
    stages {
        stage('Build') {
        	steps {
        	    sh 'mvn test Djdk.net.URLClassPath.disableClassPathURLCheck=true'        	    
        	}           
        }        
    }    
}
