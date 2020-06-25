pipeline {
   agent any

   stages {
      stage('Checkout from SCM') {
         steps {
            echo 'Get'
         }
      }
      stage('Execute Unit Tests') {
         steps {
            echo 'Hello World'
         }
      }     
      stage('Generate Build') {
         steps {
            echo 'Hello World'
         }
      }
      stage('Integration Tests') {
         steps {
            echo 'Hello World'
         }
      }
      stage('Deploy to Staging and Regression Tests') {
         steps {
            echo 'Hello World'
         }
     }
      

      stage('Deploy to Production') {
      input {
                message 'Are you sure you want to deploy to production'
       }
 
         steps {
            echo 'Hello World'
         }
      }
   }
}