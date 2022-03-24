pipeline {
    agent { label 'java' }
    stages {
        stage('checkout') { 
            steps {
              parallel(
              a: {
              sh  'im shashank c'
            },
              b: {      
              sh 'im from mysor'
            },
              c: {      
              sh  'im learning jenkine'
            }
          )     
       }
    }
  }
}
