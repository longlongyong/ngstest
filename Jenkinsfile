pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'hallo'
      }
    }
    stage('Backup') {
      steps {
        sh '''touch ~/test.txt
tar -cvzf ~/test.tar.gz ~/test.txt'''
      }
    }
    stage('Deploy') {
      steps {
        echo 'Eeeeeeend!!!'
      }
    }
  }
}