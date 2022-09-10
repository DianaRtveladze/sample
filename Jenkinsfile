pipeline {
  agent any
  stages {
    stage('Run Project') {
      parallel {
        stage('Run Project') {
          steps {
            bat 'mvn test'
          }
        }

        stage('Get version') {
          steps {
            bat 'mvn --version'
          }
        }

      }
    }

  }
}