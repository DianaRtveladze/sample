pipeline {
  agent any
  stages {
    stage('Run Project') {
      parallel {
        stage('Run Project') {
          steps {
            sh 'mvn clean test'
          }
        }

        stage('Get version') {
          steps {
            sh 'mvn -version'
          }
        }

      }
    }

  }
}