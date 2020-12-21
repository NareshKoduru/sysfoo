pipeline{

  agent any 

  tools{
    maven 'Default'
  }

  stages{ 
    
    stage('Build'){
      steps{
        sh 'mvn compile'
      }
    }

    stage('Unit Test'){
      steps{
        sh 'mvn clean test'
      }
    }

    stage('Package'){
      steps{
       sh 'mvn package -DskipTests'
      }
    }
  }

}
