pipeline {
   agent any
   tools {
     // Install the Maven version configured as "M3" and add it to the path.
     maven "M3"
     jdk "jdk8"
  }
   stages {
      stage('Build') {
         steps {
          //  sh 'mvn clean package -Dmaven.test.skip=true'
          sh 'cd target'
          sh 'java -jar *.jar'
         }
      }
   }
}
