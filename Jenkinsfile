pipeline {
  agent { label "12Sept-Node" }
  stages {
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
