pipeline {
  agent any
  stages {
    stage('s3') {
      steps {
        withAWS(region:'ap-south-1'){
          s3Upload(bucket: 'uat-artifacts', file: 'createuser.sql', workingDir: '/home/saurabh')
        }            
      }    
    }
  }            
}
