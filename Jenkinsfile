pipeline {   
    agent any

    stages {   
        stage('Backend branch') { 
            steps { 
               sh 'echo "This is backend development branch"' 
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

