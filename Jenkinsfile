pipeline {
   agent any
   tools {
      maven 'Maven'
   }
   stages {
       stage("buildmb3") {
           steps {
              snDevOpsStep()
               echo "Building" 
               sleep 5
           }
       }
       
       stage("testmb3") {
          steps {
             snDevOpsStep()
               echo "Testing" 
               sleep 5
           }           
        }
      }
  }
