pipeline {
  agent any
  stages {
    stage('s3') {
      steps 
        {
          withCredetntials('925d859d-fb27-4a15-a104-bbf143fd4788')
          {
            s3Upload(bucket: 'uat-artifacts', file: 'createuser.sql', workingDir: '/home/saurabh')
          }
        }
        
      }
  }
}
