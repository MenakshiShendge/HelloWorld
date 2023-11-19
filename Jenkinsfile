pipeline {
    agent any
    stages {
        stage('git repo & clean') {
            steps {
                bat "rmdir  /s /q HelloWorld"
            
                bat "git clone https://github.com/MenakshiShendge/HelloWorld.git"
               
            }
        }
        
        }
    }
