pipeline {
  agent any
  stages {
    stage('Cloning Git') {
      steps {
        git([url: 'https://github.com/prayag-sangode/seleniumpython.git', branch: 'main', credentialsId: 'github-id'])

      }
     }
    stage('build') {
      steps {
        sh 'python3 webtest.py'
            }
        }
    }
  }
