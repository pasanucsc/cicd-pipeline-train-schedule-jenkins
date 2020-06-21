pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        echo 'builduing'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
    }
  }
}
