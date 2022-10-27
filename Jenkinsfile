pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'C:\\Users\\friverob\\AppData\\Local\\Programs\\Python\\Python310\\python.exe --version'
      }
    }
    stage('hello') {
      steps {
        bat 'C:\\Users\\friverob\\AppData\\Local\\Programs\\Python\\Python310\\python.exe hello.py'
      }
    }
  }
}
