pipeline {
  agent {
    docker {
      image 'testimage'
    }
    
  }
  stages {
    stage('infostage') {
      steps {
        echo 'Hello'
      }
    }
  }
}