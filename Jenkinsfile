pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'echo "hello build stage"'
      }
    }

    stage('stage2') {
      steps {
        sh 'echo "hello test stage"'
      }
    }

    stage('stage3') {
      steps {
        sh 'echo "hello deploy stage"'
      }
    }

  }
}