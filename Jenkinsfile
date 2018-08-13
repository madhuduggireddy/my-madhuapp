pipeline {
  agent none
  stages {
    stage('Madhuserver') {
      agent any
      steps {
        git(url: 'https://github.com/madhuduggireddy/my-madhuapp.git', branch: 'master', credentialsId: 'test')
        bat 'mvn clean package'
      }
    }
  }
}