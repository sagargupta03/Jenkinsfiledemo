pipeline {
   agent any

   stages {
      stage('Testing') {
         steps {
            echo 'Testing'
         }
      }
	  
	  stage('Input') {
         
			input {
             message 'Is testing successful?'
			}
			steps {
			echo 'input'
         }
      }
	  
      stage('Build') {
         steps {
            echo 'Build'
         }
      }
   }
}
