pipeline {
  agent any
  stages {
    stage('Run Project') {
      parallel {
        stage('Run Project') {
          steps {
            sh 'mvn test'
          }
        }

        stage('Get version') {
          steps {
            sh 'mvn --version'
          }
        }

      }
    }

  }
}