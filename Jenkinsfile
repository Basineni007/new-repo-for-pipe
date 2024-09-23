pipeline {
	agent any
		stages{ 
			stage('compile')
			{steps
			 {
				 bat'mvn compile'}
			 }
			stage("clean package")
			{steps{
				
			
				bat'mvn package'}
		}
		}

         }

