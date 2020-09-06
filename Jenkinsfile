pipeline {
  agent any
  stages {
    stage('SimpleBuild') {
      steps {
        sh './builds/build.sh'
      }
    }

    stage('SimpleTest') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}