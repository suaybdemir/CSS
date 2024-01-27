pipeline {
  agent {
    node {
      label 'any'
    }

  }
  stages {
    stage('Clean') {
      steps {
        bat 'mvn -DskipTests clean'
      }
    }

    stage('Compile') {
      steps {
        bat 'mvn -DskipTests compile'
      }
    }

  }
}