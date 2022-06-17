pipeline {
   agent any
     tools {nodejs "nodejs"}
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
               echo 'New Build'
               echo "Running Build : ${env.BUILD_ID} on ${env.JENKINS_URL} Job: ${env.BUILD_URL}"
            }
        }
        stage ('Install'){
             steps {
        echo 'New update'
      }
        }
        stage('Commit change') {
           steps{
                 //sh 'npm test'
                echo 'New Commit'
  }
    }
    }
}
