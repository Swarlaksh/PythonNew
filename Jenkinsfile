pipeline{
  agent any 
  stages{
    stage('CICD'){
      steps{
         sh 'pip install boman-cli'
         sh ' ~/.local/bin/boman-cli -a run'
         sh 'pip3 install semgrep'
      }
    }
  }
}
