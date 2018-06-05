pipeline {
  agent {
    node {
      label 'Test'
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