pipeline {
  agent any
      
  triggers {
        eventTrigger simpleMatch("startDeploy")
  }
  
  stages {
    
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
