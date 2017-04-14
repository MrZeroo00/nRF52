pipeline {
  agent any
  stages {
    stage('Make') {
      steps {
        sh '''cd examples/peripheral/blinky/pca10036/blank/armgcc/
make'''
      }
    }
  }
}