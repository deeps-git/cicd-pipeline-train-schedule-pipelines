
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running build automation'
        sh 'java -version'
        sh './gradlew build' 
      }
    } 
  }
}
