pipeline {
  agent any
  stages {
    stage('SimpleBuild') {
      steps {
        sh 'sh \'mvn build\''
      }
    }

    stage('SimpleTest') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}