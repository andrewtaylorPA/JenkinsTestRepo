pipeline {
  agent any
  stages {
    stage ('stage_name') {
      steps {
        script {
          sh 'mkdir ~/jenkins-test'
        }
      }
    }
// 2 slashed to comment
    stage('make files'){
      steps{
        sh 'touch ~/jenkins-test/file1.txt'
      }
    }
  }
}
