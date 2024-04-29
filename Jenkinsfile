pipeline {
  agent any
  stages {
    stage ("Check Installations"){
      steps{
        sh 'git -v'
      }
    }
    stage("Stage 1") {
      steps {
        sh '''
          echo "Hello World"
          docker --version
          echo "Done for the Day"
        '''
      }
    }
  }
}
