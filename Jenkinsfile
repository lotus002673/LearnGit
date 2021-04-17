pipeline {
  agent any
  stages {
    stage('step01') {
      agent any
      steps {
        bat(returnStatus: true, script: 'echo 1')
        bat(script: 'echo 2', returnStatus: true)
        fileExists 'file1'
        echo 'this is my first blueocean work'
      }
    }

  }
}