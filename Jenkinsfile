pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'du -sh'
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
