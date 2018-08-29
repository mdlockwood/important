pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello Build'
        sleep 10
        echo 'Done Sleeping'
        sleep 5
        sleep 2
      }
    }
    stage('Test') {
      steps {
        echo 'Hello Test'
        sleep 10
      }
    }
    stage('Deploy') {
      steps {
        echo 'Hello Deploy'
        sleep 10
      }
    }
  }
}