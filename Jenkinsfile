pipeline{
	agent any
		stages{
			stage('1 make a left'){
				steps{
					sh 'echo "walk..."'
				}
			}
			stage('2 make a right'){
				steps{
					sh   'echo "walk..."'
				}
			}
			stage('3-make a left'){
				steps{
					sh 'echo "walk..."'
				}
			}
			stage('4-make a right'){
				steps{
					sh 'echo "cross the road..."'
				}
			}
			stage('5-run system analysis'){
				steps{
					sh 'lsblk'
				}
			}
			stage('6-check working directory'){
				steps{
					echo "My git is successful"
				}
			}
		}
}