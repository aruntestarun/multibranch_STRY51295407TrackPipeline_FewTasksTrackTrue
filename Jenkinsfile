pipeline {
   agent any
   tools {
      maven 'Maven'
   }
   stages {
       stage("buildmb3") {
           steps {
               echo "Building" 
               sleep 5
           }
       }
       
       stage("testmb3") {
          steps {
               echo "Testing" 
               sleep 5
           }           
        }
      }
  }
