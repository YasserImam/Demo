pipeline {
  
  agent any
  environment {
    NEW_VERSION = '1.3.0'
  }
  tools {
    maven 'maven 3.8.6'
  }
 
 stages {
    
    stage("build") {
      steps {
        echo 'Building the application..'
        sh 'mvn install'
      }
    }
    
    stage("test") {
      steps {
        echo 'Testing the application..'
      }
    }
    
    stage("deploy") {
      steps {
        echo'Deloying the application..'
      }
    }
  }
}
