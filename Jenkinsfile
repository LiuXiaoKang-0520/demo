pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            sh 'mvn clean package -Dmaven.test.skip=true'
         }
      }
   }
}
