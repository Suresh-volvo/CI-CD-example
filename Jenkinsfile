pipeline {
    agent any
    
    stages {
        stage ('Checkout') {

            steps {
                    
                echo 'checkout' 
            }
        }

       stage ('Compile Stage') {

            steps {
                
                    echo 'Compile '
                
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
