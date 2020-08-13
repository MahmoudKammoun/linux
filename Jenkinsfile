pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git 'https://github.com/MahmoudKammoun/linux.git'
      }
    }
    stage('Configure') {
      steps {

        sh label: '', script: 'cp -v /boot/config-$(uname -r) .config'
      }
    }

   
  }
