node('nodejs') {
  stage 'build'
  openshiftBuild(buildConfig: 'nodejs', showBuildLogs: 'true')
  stage 'deploy'
  openshiftDeploy(deploymentConfig: 'nodejs')
}

