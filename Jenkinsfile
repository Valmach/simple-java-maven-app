pipeline {
  agent any
  stages {
    stage('Initialise') {
      steps {
        retry(count: 10)
        echo 'This is a minimal pipeline'
      }
    }
  }
}