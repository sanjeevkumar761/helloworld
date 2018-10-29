pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('build1') {
      steps {
        sh 'npm config ls'
      }
    }
  }
}