pipeline {
          agent any
          environment {
              PYTHON_HOME = 'C:\\Users\\troyr\\AppData\\Local\\Programs\\Python\\Python312'
              PATH = "${env.PATH};${PYTHON_HOME}"
          }
          stages {
              stage('Build') {
                  steps {
                      script {
                          
                          sh 'python --version'
                          
                      }
                  }
              }
          }
      }

