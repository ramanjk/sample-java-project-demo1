pipeline {
  agent {
    docker {
      image 'centos:latest'
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
        sh 'echo "Building the code"'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Deploying the software on kubernetes"'
      }
    }

  }
}
