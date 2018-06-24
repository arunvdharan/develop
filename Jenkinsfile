pipeline {
  agent any
  stages {
    stage('initialise') {
      steps {
        sh ''' def mavenHome  = tool \'maven\'
 def docker = tool \'docker\''''
      }
    }
  }
}