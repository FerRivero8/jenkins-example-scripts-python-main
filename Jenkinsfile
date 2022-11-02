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
    stage('Pytest') {
      steps {
        bat 'C:\Users\friverob\AppData\Local\Programs\Python\Python310\Scripts\pytest.exe --version'
      }
    }
  }
}
