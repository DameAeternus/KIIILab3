pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/DameAeternus/KIIILab3.1/tree/master', branch: 'master', credentialsId: 'dd-github')
      }
    }

  }
}