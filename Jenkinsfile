pipeline {
    agent any
    
    stages {
        stage ('Checkout') {

            steps {
                    
                bat 'checkout' 
            }
        }

       stage ('Compile Stage') {

            steps {
                
                    bat 'Compile '
                
            }
        }

        stage ('Testing Stage') {

            steps {
                
                    bat ' test'
                
            }
        }


        stage ('Deployment Stage') {
            steps {
               
                    bat ' deploy'
                
            }
        }
    }
}
