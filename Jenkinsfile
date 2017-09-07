// start of pipeline
pipeline {
  // where pipeline job will run
  agent {
     label "windows_slave1"
  
  }
  
  // start of stages : build, test, deploy ...
  stages {
    // start of stage : build
    stage('build') {
      // start of running steps inside one stage
      steps {
        // invoke command to build with maven
        bat 'mvn clean install'
      }
    }
  
  }	
}

