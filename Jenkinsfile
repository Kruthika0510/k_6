pipeline{
  Agent any
    tools {
       mvn 'maven'
        }
     stages{
       stage('build'){
          steps{
          bat 'mvn clean install'
        }
     }
  }
}