pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Test-1') {
      steps {
        sh 'node --version'
      }
    }
    
    stage('Test-2') {
      steps {
        sh 'ls -lhtr; pwd; echo "versio1"'
     }
    }
  }
}
