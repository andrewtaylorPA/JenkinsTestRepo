pipeline {
  agent {
    label 'worker'
  }
  stages {
    stage ('build') {
      steps {
        script {
          sh 'echo "Build stage"'
        }
      }
    }
// 2 slashed to comment
    stage('deploy'){
      steps{
        sh 'echo "deploy stage"'
      }
    }
    stage('test'){
      steps{
        sh 'echo "test stage"'
      }
    }
  }
}
