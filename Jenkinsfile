pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Stage'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing phase'
      }
    }
    stage('Approval') {
      steps {
        echo 'Adding Approval from jira'
      }
    }
    stage('End') {
      steps {
        echo 'End Pipeline'
      }
    }
  }
}