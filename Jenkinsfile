pipeline {
  agent any
  stages {
    stage('s3 upload') {
      steps {
        s3Upload(bucket: 'uat-artifacts', file: 'createuser.sql', workingDir: '/home/saurabh/')
      }
    }
  }
}