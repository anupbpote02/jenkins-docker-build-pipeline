pipeline{
 agent any
  stages{
    stage("Git Checkout"){
       steps{
        checkout scm
       }
      }
     stage ('docker build image') { 
        steps {  
                 ps 'docker login '
                 ps 'docker build -t anupbpote/myimage5 . '
                }
            }
     }
    }
