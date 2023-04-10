pipeline{
		agent any 
			stages{
				stage('Build code'){
					steps{
						sh ' echo "Building Artifacts" '
                        echo "working on the multijob project"
		}

	}
            stage ('Testing code'){
                     steps{
                        echo " I am learning develops"
                        sh ' echo "testing my application with Sonarqube" '
                     }
    }
			stage('Deploy code'){
				steps{
					sh ' echo "Deploy Code" ' 
				}

			}
	}
}