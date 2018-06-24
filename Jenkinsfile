pipeline {
  agent any
  stages {
    stage('a') {
      parallel {
        stage('a') {
          steps {
            sh 'ls '
          }
        }
        stage('b') {
          steps {
            echo 'xxx'
          }
        }
      }
    }
    stage('e') {
      steps {
        sh 'ls'
      }
    }
  }
}