node {
    stage ('scm checkout') {  
    git ' https://github.com/mano407/repo.git'
    }
  }
  stage('compile-package') {
  sh 'mvn package'
  }
  
