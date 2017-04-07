pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        parallel(
          "build": {
            sh 'echo build'
            
          },
          "": {
            sh 'echo build2'
            
          }
        )
      }
    }
    stage('publish') {
      steps {
        sh 'echo publish'
      }
    }
  }
}