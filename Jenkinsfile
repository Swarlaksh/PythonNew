pipeline{
  agent any 
  stages{
    stage('CICD'){
      steps{
         sh 'sudo pip install boman-cli'
         sh 'sudo ~/.local/bin/boman-cli -a run'
      }
    }
  }
}
