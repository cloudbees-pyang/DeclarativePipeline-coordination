pipeline {
  agent any
  stages {
    
    triggers {
        eventTrigger simpleMatch("helloWorld")
    }
    
    stage('Pre-production') {
      steps {
        sh 'echo unit pre-production...'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo Deploying...'
      }
    }
  }
}
