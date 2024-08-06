pipeline {
  agent {label 'nodee1'}
  stages {
    stage ('BUILD') {
     agent {label 'slave2'}
      steps {
           echo "This is build stage"
           sh 'sleep 5'
         }
       }  

        stage ('TEST') { 
         agent {label 'slave2'}
          steps {
             echo "This is test stage"
             sh 'sleep 5'
         }
      } 

        stage ('DEPLOY') {
         agent {label 'slave2'}
          steps {
            echo "This is deploy stage"
            sh 'sleep 5'
      }
    }
  } 
}
