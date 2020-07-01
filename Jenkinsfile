JAVA_HOME = "/etc/alternatives/jre_1.8.0_openjdk";

pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running build automation'
        sh 'java -version  && export PATH=/Library/Java/JavaVirtualMachines/jdk1.8.0_251.jdk/Contents/Home/bin:$PATH && java -version'
        sh './gradlew build' 
      }
    } 
  }
}
