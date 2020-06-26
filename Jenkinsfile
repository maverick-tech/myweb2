pipeline {
    agent any
    tools {
        go 'go-1.14.4'
    }
    stages {
  		stage('Build') {
	    steps {
	      withEnv(["PATH+EXTRA=${HOME}/go/bin"]){
	        sh 'go build'
	      }
	    }
	  }
	} 
}
