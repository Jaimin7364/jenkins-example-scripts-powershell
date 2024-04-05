pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'ls -l'
      }
    }
    stage('hello') {
      steps {
        sh 'pwsh hello.ps1'
      }
    }
  }
}
