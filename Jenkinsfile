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
        build 'pom.mvn'
      }
    }
  }
}