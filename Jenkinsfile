pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello'
      }
    }
    stage('ls') {
      steps {
        sh 'dir'
        build 'pom.mvn'
      }
    }
  }
}