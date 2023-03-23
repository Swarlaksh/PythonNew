pipeline{
  agent any 
  stages{
    stage('CICD'){
      steps{
         sh 'echo <swarna> sudo -S pip install boman-cli' 
         sh ' ~/.local/bin/boman-cli -a run'
      }
    }
  }
}
