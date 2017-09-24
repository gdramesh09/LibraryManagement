pipeline {
  agent any
  stages {
    stage('Check out') {
      steps {
        echo 'Build is success'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
  environment {
    library = 'library'
  }
}