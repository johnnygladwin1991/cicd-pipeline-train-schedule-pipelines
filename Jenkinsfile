pipeline{
 agent any
 stages{
   stage('Build'){
    steps{ 
     echo 'Ruuning Build Automation'
      sh './gradlew build --no daemon'
    archiveArtifacts artifacts: 'dist/trainscedhuel.zip'
   }
  }
 }
} 
