pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version'
      }
    }
    stage('hello') {
      steps {
        bat 'python hello.py'
      }
    }
    stage('Mostrar_pip') {
      steps {
        bat 'pip list'
      }
    }
  }
}
