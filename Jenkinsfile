pipeline {
  agent {
    node {
      label 'Test'
    }

  }
  stages {
    stage('Clone Git Repo') {
      steps {
        sh 'echo "Cloning Git repo"'
      }
    }

    stage('Build') {
      steps {
        sh 'echo "Doing a build"'
      }
    }

  }
}