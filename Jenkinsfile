pipeline {
  agent {
    label 'jdk9'
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