pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/underdorff18/curriculum-app', branch: 'master')
      }
    }

    stage('log') {
      steps {
        sh 'ls -la'
      }
    }

  }
}