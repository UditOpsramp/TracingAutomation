pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('AutomationTesting') {
      steps {
        sh 'python3 TracingAutomation/TracingValidation.py'
      }
    }
  }
} 