pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }

    stage('Run') {
      steps {
        sh '''
          echo "Webhook triggered Jenkins!"
          date
          ls -la
        '''
      }
    }
  }
}
