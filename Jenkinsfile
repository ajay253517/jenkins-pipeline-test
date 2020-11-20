pipeline {
    agent none

    stages {
        stage('Build') {
			agent any
			options { 
				skipDefaultCheckout() 
			}

            steps {                
                echo 'Runs when skipDefaultCheckout'
            }
        }
    }
}
