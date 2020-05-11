pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'sh "Hello World"'
        echo 'This is the $BUILD_NUMBER '
      }
    }

  }
  environment {
    DEMO = '1'
  }
}