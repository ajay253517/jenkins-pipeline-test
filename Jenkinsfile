pipeline {
    agent any
	options {
	     skipDefaultCheckout() 
	}
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
