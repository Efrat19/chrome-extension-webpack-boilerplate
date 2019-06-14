pipeline {
  agent {
    docker {
      image 'node:11'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm run start'
      }
    }
  }
}