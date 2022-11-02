

pipeline {
  agent any
  stages {
    stage('checkOutCode') {
      parallel {
        stage('checkOutCode') {
          steps {
            git(url: 'https://github.com/Bloodraven21/curriculum-app', branch: 'dev')
          }
        }

        stage('logs') {
          steps {
            sh 'ls -la'
          }
        }

      }
    }

  }
}