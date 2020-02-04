node{
  stage('SCM Checkout'){
    git 'https://github.com/Shanmugaraj88/jenkins-mvn-pipeline'
  }
  stage('Compile-package'){
     // Get maven Home
     def mvnHome = tool name: 'maven-3', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
    }
  }
