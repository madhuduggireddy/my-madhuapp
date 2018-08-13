pipeline {
  agent none
  stages {
    stage('Madhuserver') {
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