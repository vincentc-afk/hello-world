pipeline{
    agent any
 tools {
    jdk "jdk11"
    maven "Maven 3.6.3"
 }
 stages {
     stage('build Hello-world') {
     steps {
         sh "mvn clean install package"
     }
    }
  }
}