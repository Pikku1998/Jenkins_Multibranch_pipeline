pipeline {   
    agent any

    stages {   
        stage('Frontend branch') { 
            steps { 
               sh 'echo "This is frontend development branch"' 
            }
        }
     
        stage('Test phase') { 
            steps { 
               sh 'echo "testing application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}

