pipleline {
agent any
stages {
  stage ('Build') {
    steps {
      echo 'Running build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacs: 'dist/trainSchedule.zip'
    }
  }
 }
}
