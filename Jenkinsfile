pipeline{
agent any 
  stages{
    stage('build'){
      when{
        changeRequest()
       }
      steps{
        echo "hello world changing request"
      }
     }
    }
   }
