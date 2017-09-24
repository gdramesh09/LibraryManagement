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
        build 'build \'gdramesh09/LibraryManagement/master\''
        echo 'Build sucess'
      }
    }
    stage('Deployement') {
      steps {
        echo 'Deploying code'
      }
    }
  }
  environment {
    library = 'library'
  }
}