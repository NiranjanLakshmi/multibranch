pipeline{
    agent any
    stages{
      stage('dve-deploy'){
          when{
              branch "dev"
          }
          steps{
              echo "deploy to dev environment"
          }
      }
        stage('uat-deploy'){
            when{
                branch "uat"
            }
          steps{
              echo "deploy to uat environment"
          }
      }
    }
}
 
