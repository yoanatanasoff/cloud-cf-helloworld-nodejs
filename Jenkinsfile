@Library('piper-lib-os') _
node() {
  stage('prepare') {
    checkout scm
    setupCommonPipeleneEnvironment script:this
  }
}



stage('build') {
  mtaBuild script: this
}
