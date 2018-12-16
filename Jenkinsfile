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
        readFile(encoding: 'UTF-8', file: 'note.txt')
      }
    }
  }
}