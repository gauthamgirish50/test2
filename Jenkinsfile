pipeline {
  agent none;
  stages {
    stage ('BUILD') {
     agent {label 'slave1'}
      steps {
           echo "This is build stage"
           sh 'sleep 5'
         }
       }  

        stage ('TEST') {
         agent {label 'slave'1} 
          steps {
             echo "This is test stage"
             sh 'sleep 5'
         }
      } 

        stage ('DEPLOY') {
         agent {label 'slave1'}
          steps {
            echo "This is deploy stage"
            sh 'sleep 5'
      }
    }
  } 
}
