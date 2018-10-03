pipeline {
  agent any
  stages {
    stage('Hello jenkins') {
      steps {
        echo 'Hello'
        input(message: 'Do you want to start?', ok: 'yea')
      }
    }
    stage('end') {
      steps {
        echo 'hello end'
        input(message: 'is it end?', ok: 'yea')
      }
    }
    stage('smth') {
      steps {
        sh 'echo "helloworld"'
      }
    }
  }
}