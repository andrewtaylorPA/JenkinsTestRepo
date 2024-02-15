pipeline {
  agent {
    label 'worker'
  }
  stages {
    stage ('build') {
      steps {
        script {
         sh './buildstage.sh'
        }
      }
    }
// 2 slashes to comment
    stage('deploy'){
      steps{
       sh './deploystage.sh'
      }
    }
    stage('test'){
      steps{
       sh './teststage.sh'
      }
    }
  }
}
