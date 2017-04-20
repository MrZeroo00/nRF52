pipeline {
  agent any
  stages {
    stage('Make') {
      steps {
        dir('examples/peripheral/blinky/pca10036/blank/armgcc') {
          sh 'make'
        }
      }
    }
    stage('Archiving') {
      steps {
        archiveArtifacts artifacts: 'examples/peripheral/blinky/pca10036/blank/armgcc/_build/*.hex', onlyIfSuccessful: true
      }
    }
  }
}