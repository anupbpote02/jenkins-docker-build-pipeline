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
                 sh 'docker login --username anupbpote --password-stdin @Nup_2499 '
                 sh 'docker build -t anupbpote/myimage5 . '
                }
            }
     }
    }
