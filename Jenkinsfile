pipeline {
    agent any
    tools {
        go 'go-1.14.4'
    }
    environment {
        GO111MODULE = 'on'
    }
    stages {
        stage('Compile') {
            steps {
            	sh 'go mod init'
                sh 'go build'
            }
        }
    }
}
