pipeline {
  agent {
    label 'worker'
  }
  stages {
    stage ('build') {
      steps {
        script {
          ./buildstage.sh
        }
      }
    }
// 2 slashes to comment
    stage('deploy'){
      steps{
        ./deploystage.sh
      }
    }
    stage('test'){
      steps{
        ./teststage.sh"'
      }
    }
  }
}
