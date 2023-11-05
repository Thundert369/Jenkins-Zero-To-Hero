pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'testing'
      }
      stage('Terraform Init') {
            steps {
                script {
                    sh 'terraform init'
                }
            }
        }
    }
  }
}
  
