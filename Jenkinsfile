pipeline{
    agent any
    
    environment{
        APP_NAME='MY_APP'
    }
    stages{
        stage('My First stage'){
            steps{
                script{
                    echo 'launching the first stage/step'
                    sh 'pwd'
                    sh 'touch testFile1 testFile2 testFile3'
                    sh 'ls -ltr'
                }
             }
         }
     }
  }
