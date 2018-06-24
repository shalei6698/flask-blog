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
      parallel {
        stage('e') {
          steps {
            sh 'ls'
          }
        }
        stage('') {
          steps {
            echo 'aaa'
          }
        }
      }
    }
  }
}