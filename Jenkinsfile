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
  }
}  
