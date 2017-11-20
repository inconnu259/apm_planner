pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Begin'
          }
        }
        stage('Test2') {
          steps {
            ws(dir: 'C:\\test') {
              sleep 4
              node(label: 'sgdsg') {
                build 'sdfdsf'
              }
              
            }
            
          }
        }
      }
    }
  }
  environment {
    Test = '0'
  }
}