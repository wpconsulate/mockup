pipeline {
  agent any
  stages {
    stage('Deploy') {
      environment {
        FTP_USER = 'admin_wp'
        FTP_PASS = 'CSmaAd14Wi'
      }
      steps {
        sh 'git ftp push --user $FTP_USER --passwd $FTP_PASS "ftp://116.203.127.130/public_shtml/"'
      }
    }
  }
}