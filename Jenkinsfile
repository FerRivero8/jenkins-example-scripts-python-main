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
    stage('test_dummy') {
      steps {
        bat 'echo $DUMMY'
      }
    }
  }
}
