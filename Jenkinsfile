pipeline {
	agent any
	options {
        retry(3)
    }
	stages {
		stage('Genesso-stage1') {
			steps{
				echo "Welcome to Genesso Trainings"
			}
		}
		stage('Genesso-Stage2') {
			steps{
				echo "This is the Second Stage"
				exit 1
			}
		}
	}
}
