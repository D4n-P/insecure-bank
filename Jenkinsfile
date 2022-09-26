@Library('shared-libs') _

pipeline {
  agent any
  stages {
    stage('SCA') {
      steps {
        dependencyCheck()
      }
    }
    post {
      always {
        archiveArtifacts 'dependency-check.xml'
      }
    }
  }
}
