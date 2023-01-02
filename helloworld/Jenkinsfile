pipeline {
  agent any
  tools {
    maven 'mavenjenkins' 
  }
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean build'
      }
    }
  }
}