@Library('piper-lib-os@v1.76.0') _
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
    stage('build') {
        mtaBuild script:this
    }
}
