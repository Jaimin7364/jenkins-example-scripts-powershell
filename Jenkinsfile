pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'dir'
      }
    }
    stage('hello') {
      steps {
        bat 'pwsh hello.ps1'
      }
    }
  }
}
