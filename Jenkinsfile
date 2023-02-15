pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'ls'
        sh 'java --version'
        sh 'javac Tester.java'
        echo 'Building the ByteCode for Given Java code'
      }
    }
    stage('Run') {
      steps {
        sh 'ls'
        echo 'Running the java ByteCode'
        sh 'java Tester'
      }
    }
  }
}