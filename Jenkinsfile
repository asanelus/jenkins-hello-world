pipeline {
  agent any 
  stages {
    stage('Build') {
      steps {
        script {

          sh 'javac HelloWorld.java && java HelloWorld' // Pour Java

        }
      }
    }
  }
}