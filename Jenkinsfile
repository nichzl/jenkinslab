pipeline {
  agent any
  
  /**
  triggers {
    pollSCM('H/15 * * * *')
  }
  */
  
    
  stages {
    stage('Hello') {
      steps {
        echo 'Hello'
        //sh "mvn test"
      }
    }
    stage('Compile HelloWorld.java') {
      steps {
        sh "javac HelloWorld.java"
      }
    }
    
    stage('Run HelloWorld') {
      steps {
        sh "java HelloWorld"
      }
    }
    /*
    stage('ls') {
      steps {
        readFile(encoding: 'UTF-8', file: 'note.txt')
      }
    }
    */
  }
  
  
  
    environment {
    JAVA_HOME = '/usr/lib/jvm/jdk-11.0.1'
    MAVEN_OPTS = '-Dmaven.repo.local=/opt/maven-work/.m2/repository'
  }

}
