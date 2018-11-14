pipeline {
 agent any
  stages {
   stage {'build'} {
     steps{
       echo 'running the build automation'
       sh './gradlew build --no-daemon'
       archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     }
   }
 }
}
