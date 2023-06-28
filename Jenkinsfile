pipeline {
  agent any
  options {
    buildDiscarder(logRotator(artifactDaysToKeepStr: '5', artifactNumToKeepStr: '5', daysToKeepStr: '5', numToKeepStr: '5'))
    disableConcurrentBuilds()
  }

  stages {
    stage('hello') {
      steps {
        echo "hello"
      }
    }
  }
}
