call C:/Users/apujol/PycharmProjects/appium_python/venv/Scripts/activate.bat
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
  }
}
