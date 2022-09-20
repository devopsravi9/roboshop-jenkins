pipeline {
  agent any
  options {
    ansiColor('xterm')
    }

  node {
    stage ('create job ') {
      sh 'ansible-playbook create-jobs.yml'
      }
    }
