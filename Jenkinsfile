pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hellow') {
      steps {
        echo 'Hello World!'
        sh 'java -version'
      }
    }
  }
}