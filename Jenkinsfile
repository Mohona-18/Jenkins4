pipeline {
  agent { label "12Sept-Node" }
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
          ifconfig
          echo "Done for the Day"
        '''
      }
    }
  }
}
