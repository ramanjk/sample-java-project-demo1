pipeline {
  agent {
    node {
      label 'Test'
    }

  }
  stages {
    stage('Clone GIT repo') {
      steps {
        sh 'sh \'echo "Cloning git repository"\''
      }
    }

    stage('Build') {
      steps {
        sh 'sh \'echo "Building the code"\''
      }
    }

  }
}