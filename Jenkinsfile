#Pipeline_with_stage_asking_a_input

// Declarative -DSL - Domain specific language //
pipeline
{
	agent any
	stages
	{
		stage('Build') 
		{
		steps {
			echo 'Building..'			
		      }
		}
		stage('Test')
		{
		steps {
		echo 'Testing..'
		      }
		}
		stage('Deploy')
		{
                input {
                message 'Are you sure you want to deploy to production'
                      }
		
                steps {
		echo 'Deploying....'
		      }
		}
	}
}
