pipeline{
  agent any
     stages{
       stage('Build'){
       steps{
          standardPipeline.build_code_openjdk11_maven360(currency-exchanger);
        }
       }
     }
  }
