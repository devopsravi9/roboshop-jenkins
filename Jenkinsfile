pipeline {
  agent any
  options {
    ansiColor('xterm')
    }

  stages {
    stage ('create job ') {
      steps {
        sh 'ansible-playbook create-jobs.yml'
        }
      }
    }

  }