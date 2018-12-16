pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'Hello'
      }
    }
    stage('ls') {
      steps {
        sh '''!#/bin/bash

`ls`'''
      }
    }
  }
}