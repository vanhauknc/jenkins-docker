pipeline {
  agent any
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
  }
  stages {
    stage('Clone'){
      steps{
        git 'https://github.com/vanhauknc/jenkins-docker.git'
      }
    }
  }
}
