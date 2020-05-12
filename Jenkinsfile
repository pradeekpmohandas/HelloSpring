pipeline {
  agent any
  stages {
   stage('git checkout') {
      steps{
        echo "chek out successfull"
      }
    }
    stage('mvn Build') {
      steps{
        script {
          sh "mvn clean install -U"
        }
      }
    }
}