pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'pip3 install -r requirements.txt'
      }
    }
    stage('version') {
      steps {
        sh 'python --version'
      }
    }
    stage('test') {
      steps {
        sh 'python test.py'
      }
    }
  }
}