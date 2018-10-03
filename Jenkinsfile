pipeline {
  agent any
  stages {
    stage('Hello jenkins') {
      steps {
        echo 'Hello'
        input(message: 'Do you want to start?', ok: 'yea')
      }
    }
  }
}