pipeline {
  agent {
    docker { image 'eclipse-temurin:17-jdk' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'maven --version'
      }
    }
  }
}
