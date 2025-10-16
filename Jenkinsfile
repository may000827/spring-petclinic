pipeline {
  agent any

  stages {
    // GitHub Clone
    stage('Git Clone') {
      steps {
        git url: 'https://github.com/may000827/spring-petclinic.git/', branch: 'main'
      }
    }
  }
}
