pipeline {
    agent any
    stages {
            stage ('Build') {
              steps {
               echo 'Running build Automation Build'
               sh './gradlew build --no-daemon'
               archiveArtifacts artifacts: 'dist/trainschedule.zip'
       }
    }
  }
}
