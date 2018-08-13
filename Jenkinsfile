pipeline {
  agent none
  stages {
    stage('Madhuserver') {
      agent any
      steps {
        sh 'echo "My Server"'
      }
    }
  }
  environment {
    test = 'test'
  }
}