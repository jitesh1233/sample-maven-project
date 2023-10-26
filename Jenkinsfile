pipeline {
    agent any 
    environment {
        PATH =/opt/maven/apache-maven-3.9.4/bin:$PATH
    }
    stages {
    stage('maven install') {
      steps {

        sh 'mvn clean install'

      }
    }

  }
}
