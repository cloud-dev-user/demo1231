pipeline {
  agent {
    node {
      label 'agent01'
    }

  }
  stages {
    stage('Checkout ') {
      steps {
        sh 'echo " checkout the code " '
      }
    }

    stage('build ') {
      steps {
        echo 'build is completed successfully'
      }
    }

    stage('test') {
      steps {
        sh 'echo " test is completed "'
      }
    }

    stage('deploy') {
      steps {
        echo 'deployment is done '
      }
    }

  }
}