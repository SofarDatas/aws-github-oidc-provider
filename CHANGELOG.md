## 2024-04-16

### Added
- Imports for dotenv, Aspects, and checkEnvVariables
- dotenv.config() to load environment variables from .env file
- checkEnvVariables function to check if required environment variables are set
- appAspects to store Aspects of the app
- check for APP_NAME environment variable
- variables for deployRegion, deployEnvironment, appName, and owner
- ApplyTags aspect to apply tags to resources
- stackProps object to store stack properties
- provider variable to create GithubActionsIdentityProvider
- CfnOutput to export provider information
- dotenv as a dependency in package.json
- AwsGithubOidcProviderStackProps interface
- JSDoc comments to AwsGithubOidcProviderStack class
- ProcessEnv declaration for CDK_DEPLOY_REGION, ENVIRONMENT, and OWNER environment variables
- ApplyTags class to apply tags to resources
- visit method to ApplyTags class to apply tags to taggable resources
- applyTag method to ApplyTags class to apply a single tag to a resource
- example values for APP_NAME, CDK_DEPLOY_REGION, ENVIRONMENT, and OWNER environment variables
- dependencies for dotenv and aws-cdk-github-oidc

### Changed
- AwsGithubOidcProviderStack constructor to accept props of type AwsGithubOidcProviderStackProps
- dependencies for aws-cdk-lib, constructs, aws-cdk, and typescript
- dependencies for aws-cdk-lib, constructs, aws-cdk, and typescript in package-lock.json
- AwsGithubOidcProviderStack constructor to pass stackProps to super
- tsconfig.json to remove target, module, and lib compiler options, add extends and include compiler options, and update outDir compiler option