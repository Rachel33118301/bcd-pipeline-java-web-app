pipeline {
  agent { label 'macoslsk' }
//   options {
//     buildDiscarder(logRotator(numToKeepStr: '5'))
//   }
  stages {
    stage('Tooling versions') {
      steps {
        sh '''
          docker --version
          docker compose version
        '''
      }
    }
  }
}