pipeline {
    agent any
    stages {
       stage('---clean---') {
          steps { 
             sh "/opt/mvn/apache-maven-3.6.2/bin/mvn clean"
          }
       }
       stage('--test--') {
          steps {
             sh "/opt/mvn/apache-maven-3.6.2/bin/mvn test"
          }
       }
       stage('--package--') {
          steps {
             sh "/opt/mvn/apache-maven-3.6.2/bin/mvn package"
          }
       }
    }
}  
