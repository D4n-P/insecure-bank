pipeline {
  agent any
  tools {
    maven 'Maven'
  }
  stages {
    stage('build') {
      sh 'mvn clean package'
    }
  }
}
