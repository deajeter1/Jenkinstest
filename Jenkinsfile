pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      agent any
      steps {
        echo 'Hello'
        sh 'java -version'
      }
    }
  }
}