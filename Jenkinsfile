pipeline{
 agent any
   stages{
     stage('build'){
       when{
         git tag "2.0"
        }
       steps{
         echo "hello world building tag"
         }
        }
       }
      }
