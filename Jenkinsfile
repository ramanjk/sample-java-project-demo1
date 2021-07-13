pipeline {
  agent {
    node {
      label 'Test'
    }

  }
  stages {
    stage('Clone GIT repo') {
      steps {
        sh 'echo "Clonig the repository"'
      }
    }

    stage('Build') {
      steps {
        sh  'echo "Building the code"'
      }
    }

  }
}
