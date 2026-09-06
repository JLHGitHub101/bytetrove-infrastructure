# ByteTrove Infrastructure

Terraform configuration for the AWS infrastructure supporting ByteTrove.

This repository will manage infrastructure such as Amazon S3, CloudFront, Route 53, ACM, IAM, and GitHub OIDC integration.

Existing production resources will be imported before Terraform is permitted to make changes.
