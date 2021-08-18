pipeline{
 
 environment {

        registry = "anupbpote/myimage6" 
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
                 sh "docker login -u $DOCKER_USERNAME --password-stdin $DOCKER_PASSWORD "
                 sh 'docker build -t anupbpote/myimage6 . '
                }
            }
     }
    }
