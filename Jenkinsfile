pipeline {
    

    stages {
        stage('Code') {
            steps {
                echo 'This is Cloning Code'
                
                echo 'Code cloning successful'
            }
        }
        
        stage('Build') {
            steps {
                echo 'This is building the code'
                sh 'whoami'
                
            }
        }
        
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
		
		 stage('Prod') {
            steps {
                echo 'Prod'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'This is deploying the code '
                
            }
        }
    }
}
