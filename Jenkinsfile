pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Say Hello!!!'
        sh 'java -version'
      }
    }
  }
}