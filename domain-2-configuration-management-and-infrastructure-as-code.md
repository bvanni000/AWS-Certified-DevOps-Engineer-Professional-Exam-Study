# Domain 2: Configuration Management and Infrastructure as Code - 19%
## Determine deployment services based on deployment needs
<details><summary>Demonstrate knowledge of process flows of deployment models</summary><p></p></details>
<details><summary>Given a specific deployment model, classify and implement relevant AWS services to meet requirements</summary>
<p>
* Given the requirement to have DynamoDB choose CloudFormation instead of OpsWorks
* Determine what to do with rolling updates
</p>
</details>

## Determine application and infrastructure deployment models based on business needs
<details><summary>Balance different considerations (cost, availability, time to recovery) based on business requirements to choose the best deployment model</summary><p></p></details>
<details><summary>Determine a deployment model given specific AWS services</summary><p></p></details>
<details><summary>Analyze risks associated with deployment models and relevant remedies</summary><p></p></details>

## Apply security concepts in the automation of resource provisioning
<details><summary>Choose the best automation tool given requirements</summary><p></p></details>
<details><summary>Demonstrate knowledge of security best practices for resource provisioning (e.g., encrypting data bags, generating credentials on the fly)</summary><p></p></details>
<details><summary>Review IAM policies and assess if sufficient but least privilege is granted for all lifecycle stages of a deployment (e.g., create, update, promote)</summary><p></p></details>
<details><summary>Review credential management solutions (e.g., EC2 parameter store, third party)</summary><p></p></details>
<details><summary>Build the automation</summary>
<p>
* CloudFormation template, Chef Recipe, Cookbooks, Code pipeline, etc.
</p>
</details>

## Determine how to implement lifecycle hooks on a deployment
<details><summary>Determine appropriate integration techniques to meet project requirements</summary><p></p></details>
<details><summary>Choose the appropriate hook solution (e.g., implement leader node selection after a node failure) in an Auto Scaling group</summary><p></p></details>
<details><summary>Evaluate hook implementation for failure impacts (if a remote call fails, if a dependent service is temporarily unavailable (i.e., Amazon S3), and recommend resiliency improvements</summary><p></p></details>
<details><summary>Evaluate deployment rollout procedures for failure impacts and evaluate rollback/recovery processes</summary><p></p></details>

## Apply concepts required to manage systems using AWS configuration management tools and services
<details><summary>Identify pros and cons of AWS configuration management tools</summary><p></p></details>
<details><summary>Demonstrate knowledge of configuration management components</summary><p></p></details>
<details><summary>Show the ability to run configuration management services end to end with no assistance while adhering to industry best practices</summary><p></p></details>