pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo \'build\''
      }
    }

    stage('test') {
      steps {
        sh 'echo \'test\''
      }
    }

  }
  environment {
    app = 'simple-python-pyinstaller-app'
    admin = 'czy'
  }
}