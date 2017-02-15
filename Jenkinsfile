node {
  stage 'build' 
	openshiftBuild(buildConfig: 'playlist-editor', showBuildLogs: 'true')
  stage 'deploy' 
	openshiftDeploy(deploymentConfig: 'playlist-editor')
 
}
