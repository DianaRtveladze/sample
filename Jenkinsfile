pipeline {
  agent any
  stages {
    stage('Run Project') {
      parallel {
        stage('Run Project') {
          steps {
            sh 'mvn clean install'
          }
        }

        stage('Get Version') {
          steps {
            sh 'mvn -version'
          }
        }

      }
    }

  }
}