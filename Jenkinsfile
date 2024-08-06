pipeline {
  agent any;
  stages {
    stage ('BUILD') {
     agent {'slave1'} 
      steps {
           echo "This is build stage"
           sh 'sleep 5'
         }
       }  

        stage ('TEST') {
         agent {'slave1'} 
          steps {
             echo "This is test stage"
             sh 'sleep 5'
         }
      } 

        stage ('DEPLOY') {
         agent {'slave1'}
          steps {
            echo "This is deploy stage"
            sh 'sleep 5'
      }
    }
  } 
}
