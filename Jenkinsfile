pipeline{
		agent any 
			stages{
				stage('1-Build code'){
					steps{
						sh ' echo "Building Artifacts" '
                        echo "working on the multijob project"
		}

	}
            stage ('2-Testing code'){
                     steps{
                        echo " I am learning develops"
                        sh ' echo "testing my application with Sonarqube" '
                     }
    }
			stage('3-Deploy code'){
				steps{
					sh ' echo "Deploy Code" ' 
				}
			}
            stage('4-Backing up the Artifacts'){
                steps{
                    sh 'lscpu'
                    echo "this is the last stage in this file"
                    sh 'lsblk'
                    sh ' echo "This is Jenkins Module " '
                }
            }
	}
}