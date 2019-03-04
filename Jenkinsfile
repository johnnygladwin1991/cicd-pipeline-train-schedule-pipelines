pipeline{
 agent any
 stages{
  Stage('Build'){
   Steps{ 
    echo 'Ruuning Build Automation'
    sh './gradlew build --no daemon'
    archiveArtifacts artifacts: 'dist/trainscedhuel.zip'
    }
   }
  }
 } 
