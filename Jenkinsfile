pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/moku828/sh7262_bootrom', branch: 'sh2a_isa_test')
      }
    }
    stage('build') {
      steps {
        sh 'make'
      }
    }
  }
}