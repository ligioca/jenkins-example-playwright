pipeline {
  agent { dockerfile true }
  stages {
    stage('test') {
      steps {
        sh '''
          node --version
          git --version
          curl --version
        '''
      }
    }
    }
  }
