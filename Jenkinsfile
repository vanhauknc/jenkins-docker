pipeline {
  agent any
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
  }
  stages {
    stage('Test1'){
      
    }
    stage('Build') {
      steps {
        sh 'docker build -t vanhauknc/jenkins-docker-hub .'
      }
    }
    
  }
}
