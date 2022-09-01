pipeline {
  agent any
  stages {
    stage('Cloning Git') {
      steps {
        git([url: 'https://github.com/prayag-sangode/seleniumpython.git', branch: 'main'])

      }
     }
    stage('build') {
      steps {
        sh 'python3 webtest.py'
            }
        }
    }
  }
