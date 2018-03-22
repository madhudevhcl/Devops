pipeline {
    agent any 
    stages {
	stage('clone sources') { 
            steps {
                git url: 'https://github.com/madhudevhcl/Devops.git' 
            }
        }
        stage('Build') { 
            steps {
                mvn 'validate' 
            }
        }
        stage('Test') { 
            steps {
               echo " Test success" 
            }
        }
        stage('Deploy') { 
            steps {
                echo " Deploy success" 
            }
        }
    }
}