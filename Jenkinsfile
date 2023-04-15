#!groovy

pipeline {
	agent none
  stages {
    stage('Docker Build') {
    	agent any
      steps {
      	sh 'docker build -t "my_app $BUILD_NUMBER" .'
      }
    }
  }
}
