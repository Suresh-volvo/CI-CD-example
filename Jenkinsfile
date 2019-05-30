pipeline {
    agent any
    
    stages {
        stage ('Checkout') {

            steps {
                    
                sh 'checkout' 
            }
        }

       stage ('Compile Stage') {

            steps {
                
                    sh 'Compile '
                
            }
        }

        stage ('Testing Stage') {

            steps {
                
                    sh ' test'
                
            }
        }


        stage ('Deployment Stage') {
            steps {
               
                    sh ' deploy'
                
            }
        }
    }
}
