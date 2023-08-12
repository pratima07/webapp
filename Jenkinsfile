pipeline {
   agent any 
  tools {
     maven 'Maven'
  }
   
   stages {
        stage ('Build') {
          sh 'mvn clean package'

        }
   }

}
