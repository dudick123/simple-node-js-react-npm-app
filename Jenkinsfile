pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh \'./jenkins/scripts/diag.sh\''
      }
    }
  }
}