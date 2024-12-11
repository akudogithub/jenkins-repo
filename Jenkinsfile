pipeline{
	agent any
		stages{
			stage('git clone'){
				steps{
					sh ' echo "testing jenkins pipeline" '
				}
			}
			stage('system update'){
				steps{
					sh 'cat /etc/passwd'
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
