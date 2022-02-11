pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
        sh 'mvn clean'
      }
    }
    stage('Package') {
      steps {
        sh 'mvn -Dmaven.test.skip=true package'
      }
    }
  }
}
