pipeline{
  agent any 
  stages{
    stage('CICD'){
      steps{
         sh 'pip install --user boman-cli'
         sh ' ~/.local/bin/boman-cli -a run'
      }
    }
  }
}
