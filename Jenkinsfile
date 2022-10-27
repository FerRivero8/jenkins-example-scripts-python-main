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
        bat 'C:\\Users\\friverob\\AppData\\Local\\Programs\\Python\\Python310\\python.exe hello.py'
      }
    }
    stage('test_dummy') {
      steps {
        bat 'echo DUMMY'
      }
    }
  }
}
