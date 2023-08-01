# Domain 1: SDLC Automation - 22%

## Task Statement 1.1: Implement CI/CD pipelines

### Knowledge of:
<details><summary>Software development lifecycle (SDLC) concepts, phases, and models</summary><p></p></details>
<details><summary>Pipeline deployment patterns for single- and multi-account environments</summary><p></p></details>

### Skills in:
<details><summary>Configuring code, image, and artifact repositories</summary><p></p></details>
<details><summary>Using version control to integrate pipelines with application environments</summary><p></p></details>
<details><summary>Setting up build processes (for example, AWS CodeBuild)</summary><p></p></details>
<details><summary>Managing build and deployment secrets (for example, AWS Secrets Manager, AWS Systems Manager Parameter Store)</summary><p></p></details>
<details><summary>Determining appropriate deployment strategies (for example, AWS CodeDeploy)</summary><p></p></details>

## Task Statement 1.2: Integrate automated testing into CI/CD pipelines
### Knowledge of:
<details><summary>Different types of tests (for example, unit tests, integration tests, acceptance tests, user interface tests, security scans)</summary>
 <p>
  * unit tests: define...
  * integration tests
  * acceptance tests
  * user interface tests
  * security scans
  ** static
  ** dynamic
 </p>
</details>
<details><summary>Reasonable use of different types of tests at different stages of the CI/CD pipeline</summary><p></p></details>

### Skills in:
<details><summary>Running builds or tests when generating pull requests or code merges (for example, AWS CodeCommit, CodeBuild)</summary><p></p></details>
<details><summary>Running load/stress tests, performance benchmarking, and application testing at scale</summary><p></p></details>
<details><summary>Measuring application health based on application exit codes</summary><p></p></details>
<details><summary>Automating unit tests and code coverage</summary><p></p></details>
<details><summary>Invoking AWS services in a pipeline for testing</summary><p></p></details>

## Task Statement 1.3: Build and manage artifacts
### Knowledge of:
<details><summary>Artifact use cases and secure management</summary><p></p></details>
<details><summary>Methods to create and generate artifacts</summary><p></p></details>
<details><summary>Artifact lifecycle considerations</summary><p></p></details>

### Skills in:
<details><summary>Creating and configuring artifact repositories (for example, AWS CodeArtifact, Amazon S3, Amazon Elastic Container Registry [Amazon ECR])</summary><p></p></details>
<details><summary>Configuring build tools for generating artifacts (for example, CodeBuild, AWS Lambda)</summary><p></p></details>
<details><summary>Automating Amazon EC2 instance and container image build processes (for example, EC2 Image Builder)</summary><p></p></details>

## Task Statement 1.4: Implement deployment strategies for instance, container, and serverless environments
### Knowledge of:
<details><summary>Deployment methodologies for various platforms (for example, Amazon EC2, Amazon Elastic Container Service [Amazon ECS], Amazon Elastic Kubernetes Service [Amazon EKS], Lambda)</summary><p></p></details>
<details><summary>Application storage patterns (for example, Amazon Elastic File System [Amazon EFS], Amazon S3, Amazon Elastic Block Store [Amazon EBS])</summary><p></p></details>
<details><summary>Mutable deployment patterns in contrast to immutable deployment patterns</summary><p></p></details>
<details><summary>Tools and services available for distributing code (for example, CodeDeploy, EC2 Image Builder)</summary><p></p></details>

### Skills in:
<details><summary>Configuring security permissions to allow access to artifact repositories (for example, AWS Identity and Access Management [IAM], CodeArtifact)</summary><p></p></details>
<details><summary>Configuring deployment agents (for example, CodeDeploy agent)</summary><p></p></details>
<details><summary>Troubleshooting deployment issues</summary><p></p></details>
<details><summary>Using different deployment methods (for example, blue/green, canary)</summary><p></p></details>


# OLD
## Apply concepts required to automate a CI/CD pipeline
<details><summary>Set up repositories</summary><p></p></details>
<details><summary>Set up build services</summary><p></p></details>
<details><summary>Integrate automated testing (e.g., unit tests, integrity tests)</summary><p></p></details>
<details><summary>Set up deployment products/services</summary><p></p></details>
<details><summary>Orchestrate multiple pipeline stages</summary><p></p></details>

## Determine source control strategies and how to implement them
<details><summary>Determine a workflow for integrating code changes from multiple contributors</summary><p></p></details>
<details><summary>Assess security requirements and recommend code repository access design</summary><p></p></details>
<details><summary>Reconcile running application versions to repository versions (tags)</summary><p></p></details>
<details><summary>Differentiate different source control types</summary><p></p></details>

## Apply concepts required to automate and integrate testing
<details><summary>Run integration tests as part of code merge process</summary><p></p></details>
<details><summary>Run load/stress testing and benchmark applications at scale</summary><p></p></details>
<details><summary>Measure application health based on application exit codes (robust Health Check)</summary><p></p></details>
<details><summary>Automate unit tests to check pass/fail, code coverage</summary><p>
  * CodePipeline, CodeBuild, etc.
</p>
</details>
<details><summary>Integrate tests with pipeline</summary><p></p></details>

## Apply concepts required to build and manage artifacts securely
<details><summary>Distinguish storage options based on artifacts security classification</summary><p></p></details>
<details><summary>Translate application requirements into Operating System and package configuration (build specs)</summary><p></p></details>
<details><summary>Determine the code/environment dependencies and required resources</summary>
<p>
  * Example: CodeDeploy AppSpec, CodeBuild buildspec
</p>
</details>
<details><summary>Run a code build process</summary><p></p></details>

## Determine deployment/delivery strategies (e.g., A/B, Blue/green, Canary, Red/black) and how to implement them using AWS services
<details><summary>Determine the correct delivery strategy based on business needs</summary><p></p></details>
<details><summary>Critique existing deployment strategies and suggest improvements</summary><p></p></details>
<details><summary>Recommend DNS/routing strategies (e.g., Route 53, ELB, ALB, load balancer) based on business continuity goals</summary><p></p></details>
<details><summary>Verify deployment success/failure and automate rollbacks</summary><p></p></details>
