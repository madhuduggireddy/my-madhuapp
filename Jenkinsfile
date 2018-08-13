pipeline {
  agent none
  stages {
    stage('Madhuserver') {
      agent any
      steps {
        sh 'echo "My Server"'
        git(url: 'https://github.com/madhuduggireddy/my-madhuapp.git', branch: 'master', credentialsId: 'test')
        bat 'git clone'
      }
    }
  }
}