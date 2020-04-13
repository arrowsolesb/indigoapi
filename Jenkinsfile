pipeline {
  agent any
  stages {
    stage('Build Application') { 
        bat 'mvn clean install'
    }
    stage('Deploy Mule Application into Cloud') { 
        bat 'mvn package deploy -DmuleDeploy'
    }
  }
    
}