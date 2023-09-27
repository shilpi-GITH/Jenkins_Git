pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'Test'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

    stage('Release') {
      steps {
        build 'Test2'
      }
    }

  }
}