pipeline {
    agent any

    // stages started 
    stages {
        stage('Windows Stage'){
            steps{
                script{
                  sample()
                  osPlatform.windows()
                }
            }
        }
        stage('Linux Stage'){
            steps{
                script{
                  osPlatform.linux()
                }
            }
        }
    }
}
