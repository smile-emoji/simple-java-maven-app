pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
        sh 'sh "mvn clean"'
      }
    }

    stage('Package') {
      steps {
        sh 'sh "\'mvn\' -Dmaven.test.skip=true package"'
      }
    }

  }
}