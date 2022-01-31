pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'ifconfig'
      }
    }

    stage('stage 2') {
      steps {
        sh 'cat /etc/os-release'
      }
    }

    stage('stage 3') {
      steps {
        sh 'free -h'
      }
    }

  }
}
