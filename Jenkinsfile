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
                 sh 'docker login /bin/bash'
                 sh 'docker build -t anupbpote/myimage5 . /bin/bash'
                }
            }
     }
    }
