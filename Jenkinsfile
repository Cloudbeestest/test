pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Test') {
      steps {
        echo 'Hello world'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}