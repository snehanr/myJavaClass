pipeline {
    agent any

    stages {
        stage('Stage One') {
            steps {
                echo 'Hello Stage One - Step 1'
		    		input('Do you want to proceed?')
				echo 'Hello Stage One - Step 1' 
				build job : "RunCodeGit"
            }
        }
		stage('Stage Two') {
            steps {
                echo 'Hello Stage Two - Step 1'
				echo 'Hello Stage Two - Step 1'
            }
        }
		stage('Stage Three') {
            steps {
                echo 'Hello Stage Three - Step 1'
				echo 'Hello Stage Three - Step 1'
            }
        }
    }
}
