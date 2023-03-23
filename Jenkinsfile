pipeline{
  agent any 
  stages{
    stage('CICD'){
      steps{
         sh 'sudo -S pip install boman-cli' 
         sh ' ~/.local/bin/boman-cli -a run'
      }
    }
  }
}
