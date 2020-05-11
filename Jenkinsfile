pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}