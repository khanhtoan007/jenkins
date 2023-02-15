pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
	stage('echo') {
	    steps {
	        echo 'Hello World!'
	    }
	}
        stage('build') {
            steps {
                sh 'python --version'
		sh 'python -h'
		echo 'Hello MF'
            }
        }
    }
}
