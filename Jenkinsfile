pipeline {
  agent {
    docker {
      image 'golang:1.10.1-alpine'
      label 'docker-cloud'
    }
    
  }
  stages {
    stage('Say hello') {
      steps {
        echo 'Hello World'
        sh 'go version'
      }
    }
  }
}