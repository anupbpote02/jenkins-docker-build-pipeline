pipeline{
 
 environment {

        registry = "anupbpote/myimage5" 
        DOCKER_USERNAME = "anupbpote"
        DOCKER_PASSWORD = "@Nup_2499"
        dockerImage = '' 

    }

 agent any
  stages{
    stage("Git Checkout"){
       steps{
        checkout scm
       }
      }
     stage ('docker build image') { 
        steps {  
                 sh "winpty docker login -u $DOCKER_USERNAME --password-stdin $DOCKER_PASSWORD "
                 sh 'winpty docker build -t anupbpote/myimage5 . '
                }
            }
     }
    }
