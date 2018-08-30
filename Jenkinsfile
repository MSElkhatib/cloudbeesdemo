pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hellow') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mohamad'
  }
}