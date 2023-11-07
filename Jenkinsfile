pipeline {
    agent any
    environment {
        name = 'Gaurav'
    }

    stages {
        stage('Command to RUN') {
            steps {
                sh '''
                ls 
                pwd 
                date || cal
                '''
            }
        }
        
        stage('Deploy the prod') {
            steps {
               echo "Deploy the prod"
            }
        }
        stage('Do you want to proceed?') {
            steps {
              input ('Do you want to proceed?')
            }
        }
        
    }
    
        }
        
