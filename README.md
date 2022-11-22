# Our reusable workflows

## Description
This repo contains all the reusable workflows we can use to build our magic pipelines 🧜

## Usages
In case of deployments that uses watchtower, please follow [this link](https://github.com/crispybaconsrl/devops-team__terraform__ecr-entities-for-external-deployments)

Other workflows basically are self-described from their name:

- azure-serverless-functions.yml => Used for deploying Azure Serverless Functions
- build-image-on-ecr-with-vault.yml => Used for building a Docker Image on ECR authenticating using Vault
- build-public-image-on-ecr-with-vault.yml => Used for building and publishing a PUBLIC image on ECR authenticating using Vault
- cloudfront-cache-invalidation.yml => Invalidation of Cloudfront Distributions authenticating using Vault
- deploy-on-ecs-with-vault.yml => Deploy on ECS Cluster authenticating using Vault
- rancher-deploy.yml => Deploy on our internal K8S cluster
