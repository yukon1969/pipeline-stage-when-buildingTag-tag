pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				tag "v2.0.1"
			}
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }
}
