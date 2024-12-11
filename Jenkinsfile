pipeline{
	agent any{
		stages{
			stage('git clone'){
				steps{
					sh ' echo "testing jenkins pipeline" '
				}
			}
			stage('system update'){
				steps{
					sh 'sudo update -y'
				}
			}
			stage('sys-resource-check'){
				steps{
					sh 'lscpu'
					sh 'lsblk'
					sh 'free -m'
				}
			}
		}
	}
}