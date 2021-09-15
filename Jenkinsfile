pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
         sh './gradlew build'
      }
    }

    stage('SaySomethingCool') {
      steps {
        sh 'echo "Say Something Cool"'
        sh 'echo "Something Coooooooooool!!!!!"'
      }
    }

    stage('AnnounceCompletion') {
      steps {
        sh 'echo "I\'m echoing Done!"'
      }
    }

    stage('Print') {
      steps {
        echo 'Printing someting from task'
      }
    }

  }
}