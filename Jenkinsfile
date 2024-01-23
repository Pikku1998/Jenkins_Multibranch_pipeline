pipeline {   
    agent any

    stages {   
        stage('Backend branch') { 
            steps { 
               sh 'echo "This is backend development branch"'

               sh 'echo "Added an update in backend."' 
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

