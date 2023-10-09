pipeline{


    agent any
    stages{
        stage('Run test'){
            steps{
                sh "docker-compose up"   
            }
        }       
        stage('sBring Grid Down'){
            steps{
                sh "docker-compose down"    
                
            }

        }

}

}