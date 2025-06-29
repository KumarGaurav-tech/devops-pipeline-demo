pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Step 1: Building the application...'
        sh 'df -PhT'
      }
    }
    stage('Test') {
      steps {
        echo 'Step 2: Running tests...'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Step 3: Deploying to staging...'
      }
    }
  }
}
