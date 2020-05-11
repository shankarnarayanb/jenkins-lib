pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'This is the $BUILD_NUMBER '
      }
    }

  }
  environment {
    DEMO = '1'
  }
}