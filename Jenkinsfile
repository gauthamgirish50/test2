pipeline {
  agent none;
  stages {
    stage ('BUILD') {
     agent {'nodee1'} 
      steps {
           echo "This is build stage"
           sh 'sleep 5'
         }
       }  

        stage ('TEST') {
         agent {'nodee1'} 
          steps {
             echo "This is test stage"
             sh 'sleep 5'
         }
      } 

        stage ('DEPLOY') {
         agent {'nodee1'}
          steps {
            echo "This is deploy stage"
            sh 'sleep 5'
      }
    }
  } 
}
