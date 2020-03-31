pipeline {
  agent any
  stages {
    stage ('Build'){
      steps : {
        echo "Running build from jenkins file. Yo Yo Akash"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
