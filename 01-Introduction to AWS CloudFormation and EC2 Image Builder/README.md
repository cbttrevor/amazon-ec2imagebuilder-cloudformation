## Learning Objectives

### What You'll Learn

* How to create EC2 Image Builder resources with AWS CloudFormation
  * Build/test components
  * Recipes
  * Distribution settings
  * Infrastructure configurations
  * Pipelines

### Notes

* EC2 Image Builder is a managed service enabling end-to-end automation of container images and Amazon Machine Images (AMI)
* CloudFormation enables you to create "infrastructure as code" templates that are deployable as a "stack" of resources
* You can use YAML or JSON syntax for your CloudFormation templates. I prefer YAML, for readability.
* CloudFormation templates can be version controlled in a source control repository (ie. Git, Mercurial)

### Prerequisites

* You should already have watched the EC2 Image Builder training
* You should know about AWS CloudFormation and how to create templates
* You should be familiar with the AWS SDKs (ie. AWS Tools for PowerShell)
* Have AWS credentials set up on your local development system
