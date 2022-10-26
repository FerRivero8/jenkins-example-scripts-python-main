pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version'
        echo 'Hello World'
      }
    }
    stage('hello') {
      steps {
        bat 'python hello.py'
      }
    }
  }
}
