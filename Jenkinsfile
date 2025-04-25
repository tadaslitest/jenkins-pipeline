pipeline {
  agent any

  environment {
    NODE_ENV = 'test'
  }

  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }

    stage('Install Dependencies') {
      steps {
        echo 'Simulating installing dependencies...'
      }
    }

    stage('Run Tests') {
      steps {
        echo 'Simulating running tests...'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Simulating deployment...'
      }
    }
  }

  post {
    success {
      echo 'Pipeline completed successfully.'
    }
    failure {
      echo 'Pipeline failed.'
    }
  }
}
