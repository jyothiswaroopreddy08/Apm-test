
pipeline{
  agent any
  
  stages{
  stage('Install'){
      steps{
        bat "npm -v"
        bat "npm install"
      }
    }
    stage('Build'){
      steps{
        bat "npm run build"
      }
    }
  }
}
