pipeline {
   agent any

   stages {
      stage('Testing') {
         steps {
            echo 'Testing'
         }
      }
	  
	  stage('Start with the build ') {
         
			input {
             message 'can we start with the build, is testing successful?'
			}
			steps {
			echo 'Proceed or abort'
         }
      }
	  
      stage('Build') {
         steps {
            echo 'Build'
         }
      }
   }
}
