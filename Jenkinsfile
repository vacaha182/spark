pipeline {
  agent any
  stages {
    stage('gg') {
      parallel {
        stage('gg') {
          steps {
            sh 'echo "hola"'
          }
        }
        stage('eeee') {
          steps {
            sh 'echo "a'
          }
        }
      }
    }
    stage('ee') {
      steps {
        sh 'echo "pasa hola"'
      }
    }
  }
}