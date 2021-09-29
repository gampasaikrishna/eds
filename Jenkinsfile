pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'jenkins Minute pipeline'
      }
    }

    stage('compile') {
      steps {
        sh 'mvn  install'
      }
    }

  }
}