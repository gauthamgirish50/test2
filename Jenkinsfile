pipeline {
  agent any;
  stages {
    stage ('BUILD') {
      steps {
             sh'''
             sleep5
             echo "This is build stage"
      }
    }

     stage ('TEST') {
      steps {
             sh'''
             sleep5
             echo "This is test stage"
      }
    }

     stage ('DEPLOY') {
      steps {
            sh'''
            sleep5
            echo "This is deploy stage"
      }
    }
  } 
}
