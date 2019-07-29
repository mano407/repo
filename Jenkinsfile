node {
    stage ('scm checkout') {
    git ' https://github.com/mano407/repo.git'
    }
  }
  stage('compile-package') {
    //get maven home path 
   def mvnhome = tool name: 'mavan', type: 'maven'
  sh "${mvnhome}/bin/mvn clean install"
  }
  
