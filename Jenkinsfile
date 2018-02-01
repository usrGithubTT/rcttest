pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        bat 'dir' 
        bat 'dir m*'
      }
    }
    stage('Build') {
      steps { 
        bat 'dir'
        bat 'dir m*'
      }
    }
  }
}
