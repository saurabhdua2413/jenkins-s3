pipeline {
  agent any
  stages {
    stage('s3') {
      steps {
        s3Upload(bucket: 'uat-artifacts', file: 'createuser.sql', workingDir: '/home/saurabh')    
      }    
    }
  }            
}
