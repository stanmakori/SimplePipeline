pipeline {
  agent any
  stages {
    stage('SimpleBuild') {
      steps {
        sh './jenkins/build.sh'
      }
    }

    stage('SimpleTest') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}