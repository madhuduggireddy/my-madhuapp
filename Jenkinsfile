pipeline {
  agent none
  stages {
    stage('Madhuserver') {
      agent any
      steps {
        sh '''echo "My Server"
mvn -version'''
      }
    }
  }
  environment {
    test = 'test'
  }
}