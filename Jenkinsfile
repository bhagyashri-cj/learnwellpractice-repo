pipeline {
  agent any{
  
          }
  stages {
    stage('build CI ') {
      steps {
        sh 'mvn clean package'
      }
    }
   }

    stage('invoke learnwell class ') {
      steps {
        sh 'java -cp target/devops-app-1.0-SNAPSHOT.jar newlearnwell.app.App '
      }
    }
    
 }
  
