pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'message'
        sh 'java -version'
      }
    }
  }
}