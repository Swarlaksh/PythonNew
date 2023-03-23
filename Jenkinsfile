pipeline{
  agent any 
  stages{
    stage('CICD'){
      steps{
         sh 'sudo -A pip install boman-cli' 
         sh ' ~/.local/bin/boman-cli -a run'
      }
    }
  }
}
