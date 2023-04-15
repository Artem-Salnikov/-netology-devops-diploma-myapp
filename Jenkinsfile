#!groovy

pipeline {
	agent none
  stages {
    stage('Docker Build') {
    	agent any
      steps {
	sh 'NOW=$(date +"%Y-%m-%d_%H-%M")'      
      	sh 'docker build -t $BUILD_NUMBER .'
      }
    }
  }
}
