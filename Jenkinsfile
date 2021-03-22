pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        sh 'sh "rsync -av shop_ban_hang_online rsync://18.204.204.30/code"'
      }
    }

  }
}