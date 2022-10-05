# Domain 1: SDLC Automation

## Apply concepts required to automate a CI/CD pipeline
* Set up repositories
* Set up build services
* Integrate automated testing (e.g., unit tests, integrity tests)
* Set up deployment products/services
* Orchestrate multiple pipeline stages

## Determine source control strategies and how to implement them
* Determine a workflow for integrating code changes from multiple contributors
* Assess security requirements and recommend code repository access design
* Reconcile running application versions to repository versions (tags)
* Differentiate different source control types

## Apply concepts required to automate and integrate testing
* Run integration tests as part of code merge process
* Run load/stress testing and benchmark applications at scale
* Measure application health based on application exit codes (robust Health Check)
* Automate unit tests to check pass/fail, code coverage
  * CodePipeline, CodeBuild, etc.
* Integrate tests with pipeline

## Apply concepts required to build and manage artifacts securely
* Distinguish storage options based on artifacts security classification
* Translate application requirements into Operating System and package configuration (build specs)
* Determine the code/environment dependencies and required resources
  * Example: CodeDeploy AppSpec, CodeBuild buildspec
* Run a code build process

## Determine deployment/delivery strategies (e.g., A/B, Blue/green, Canary, Red/black) and how to implement them using AWS services
* Determine the correct delivery strategy based on business needs
* Critique existing deployment strategies and suggest improvements
* Recommend DNS/routing strategies (e.g., Route 53, ELB, ALB, load balancer) based on business continuity goals
* Verify deployment success/failure and automate rollbacks