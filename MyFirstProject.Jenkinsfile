Pipeline {
    dockerConfig = [
      makeDirs: [ './integration_test/build/reports' ],
      reportFile: 'index.html',
      reportDir: 'integration_test/build/reports/serenity',
      makeDirs: ['integration_test/build/reports/serenity']
    ]
    buildConfig = [
      enableGradlePublish: 'true',
      enableGradlePublishBranch : 'true',
      enableSonarqube: false,
      enableOWASP: true,
      enableFortify: true
    ]
    deploymentConfig = [
       //jobs: [ '/HDXTS Swarm/TEST/hdxts-swarm-rdc-dev-devtest/master', '/HDXTS Swarm/TEST/hdxts-swarm-rdc-dev-devtestredamber/master' ],
      ]
}
