#!groovy

pipeline {
	agent none
  stages {
    stage('Docker Build') {
    	agent any
      steps {
	sh 'now=$(date)'
	sh 'echo $now'
      	sh 'docker build -t qwe .'
      }
    }
  }
}
