pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'testing'
      }
      stage ('terraform init') {
        steps {
          sh '(terraforn init)'
    }
  }
}
  }
