pipeline {
  agent any
  
  stages {
    stage('First Job') {
      steps {
        echo "Hello folks, this is our first script"
      }
    }  
    stage('Second Job') {
      steps {
        input message: 'User Input required'
      }
    }
    stage('Third Job') {
      when {
        // skipe this stage unless this is on Master branch
        branch "master"
      }
      steps {
        echo "Not Master"
      }
    }
  }
}  
