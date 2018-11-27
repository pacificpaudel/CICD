pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/pacificpaudel/CICD.git', branch: 'master', changelog: true)
      }
    }
  }
}