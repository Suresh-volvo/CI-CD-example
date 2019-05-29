pipeline {
    agent any
    
    stages {
        stage ('Checkout') {

            steps {
                    git credentialsId: '3985993c-a55b-4a0b-81da-3609e7de72cb', url: 'https://github.com/Suresh-volvo/CI-CD-example.git'
                    sh 'checkout complete '
                
            }
        }

    stages {
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
