pipeline {
  agent any
  stages {
    stage('Make') {
      steps {
        dir('cd examples/peripheral/blinky/pca10036/blank/armgcc') {
          sh 'make'
        }
      }
    }
  }
}