pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        echo 'Madhu'
      }
    }
    stage('') {
      steps {
        git(url: 'https://github.com/madhuduggireddy/my-madhuapp', branch: 'master', poll: true, changelog: true, credentialsId: 'test')
      }
    }
  }
  environment {
    test = 'test'
  }
}