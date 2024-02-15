pipeline {
  agent any
  stages {
    stage ('Permissions') {
      steps {
        script {
         sh 'chmod +x buildstage.sh'
         sh 'chmod +x deploystage.sh'
         sh 'chmod +x teststage.sh'
        }
      }
    }
    stage ('Build') {
      steps {
        script {
         sh './buildstage.sh'
        }
      }
    }
// 2 slashes to comment
    stage('Deploy'){
      steps{
       sh './deploystage.sh'
      }
    }
    stage('Test'){
      steps{
       sh './teststage.sh'
      }
    }
  }
}
