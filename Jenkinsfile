pipeline {
    agent { label 'java' }
    stages {
        stage('checkout') { 
            steps {
              parallel(
              a: {
              sh 'echo “im shashank c”'
            },
              b: {      
              sh 'echo “im from mysore”'
            },
              c: {      
              sh 'echo “im learning devops”'
            }
          )     
       }
    }
  }
}
