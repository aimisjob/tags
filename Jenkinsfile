pipeline{
 agent any
   stages{
     stage('build'){
       when{
         tag "law-*"
        }
       steps{
         echo "hello worlds building tag"
         }
        }
       }
      }
