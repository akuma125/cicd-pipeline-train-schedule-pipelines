pipleline {
agent any
stages {
 stage ('build') {
  steps {
   echo 'Running Build Automation'
    sh './gradlew build --no-demon'
    archiveArtifacts artifcats: 'dist/trainSchedule.zip'
   }
  }
 }
}
