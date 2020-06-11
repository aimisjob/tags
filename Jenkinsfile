pipeline{
 agent any
   stages{
     stage('build'){
       when{
         tag "release-*"
        }
       steps{
         echo "hello world building tag"
         }
        }
       }
      }
