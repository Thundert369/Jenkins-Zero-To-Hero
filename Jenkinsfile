pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'testing'
      }
      stage ('terraform init')
      sh '(terraform init)'
    }
  }
}
