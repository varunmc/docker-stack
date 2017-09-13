# docker-stack
_The application stack_

## Pre-Reqisites
* All `docker-*` projects

## Getting Started
The [AWS CodeFormation](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stack/detail?stackId=arn:aws:cloudformation:us-east-1:497513737772:stack%2FStack%2F57d1a150-9165-11e7-8011-500c2866f062) template _stack.yml_ will create an [AWS CodePipeline](https://console.aws.amazon.com/codepipeline/home?region=us-east-1#/view/Stack) with an [AWS CodeBuild](https://console.aws.amazon.com/codebuild/home?region=us-east-1#/projects/Stack/view) builder as defined in _buildspec.yml_. The continuous pipeline will deploy all updated applications to [AWS ECS](https://console.aws.amazon.com/ecs/home?region=us-east-1#/clusters/StagingCluster/services).

## Links
* [Docker Compose](https://docs.docker.com/compose/)
