pipeline {
  agent {
    node {
      label 'Jdk9'
    }

  }
  stages {
    stage('Test') {
      steps {
        echo 'Hello world'
        sh 'java -version'
      }
    }
  }
}