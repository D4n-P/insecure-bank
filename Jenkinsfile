@Library('shared-libs')

pipeline {
  agent any
  stages {
    stage('SCA') {
      steps {
        dependencyCheck()
      }
    }
  }
}
