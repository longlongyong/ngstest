pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'hallo'
      }
    }
    stage('error') {
      steps {
        sh '''touch test.txt
tar -cvzf ~/test.tar.gz ~/test.txt'''
      }
    }
  }
}