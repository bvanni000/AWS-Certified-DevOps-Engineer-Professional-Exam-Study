# Domain 6: High Availability, Fault Tolerance, and Disaster Recovery - 16%
## Determine appropriate use of multi-AZ versus multi-Region architectures
<details><summary>Determine deployment strategy based on HA/DR requirements</summary><p></p></details>
<details><summary>Determine data replication strategy based on cost and durability requirements</summary><p></p></details>
<details><summary>Determine infrastructure, platform, and services based on HA/DR requirements</summary><p></p></details>
<details><summary>Design for HA/FT/DR based on service availability (i.e., global/regional/single AZ)</summary><p></p></details>

## Determine how to implement high availability, scalability, and fault tolerance
<details><summary>Design deployment strategy to support HA/FT/scalability</summary><p></p></details>
<details><summary>Assess statefulness of application infrastructure components</summary><p></p></details>
<details><summary>Use load balancing to distribute traffic across multiple AZ/ASGs/instance types (spot/M4 vs C4) /targets</summary><p></p></details>
<details><summary>Use appropriate caching solutions to improve availability and performance</summary><p></p></details>

## Determine the right services based on business needs (e.g., RTO/RPO, cost)
<details>
<summary>Determine cost-effective storage solution for your application</summary>
<p>
* Example: tiered, archival, EBS type, hot/cold
</p>
</details>
<details><summary>Choose a database platform and configuration to meet business requirements</summary><p></p></details>
<details>
<summary>Choose a cost-effective compute platform based on business requirements</summary>
<p>
* Example: Spot
</p>
</details>
<details>
<summary>Choose a deployment service/model based on business requirements</summary>
<p>
* Example: Code Deploy, Blue/Green deployment
</p>
</details>
<details><summary>Determine when to use managed service vs. self-managed infrastructure (Docker on EC2 vs. ECS)</summary><p></p></details>

## Determine how to design and automate disaster recovery strategies
<details><summary>Automate failure detection</summary><p></p></details>
<details><summary>Automate components/environment recovery</summary><p></p></details>
<details><summary>Choose appropriate deployment strategy for environment recovery</summary><p></p></details>
<details><summary>Design automation to support failover in hybrid environment</summary><p></p></details>

## Evaluate a deployment for points of failure
<details><summary>Determine appropriate deployment-specific health checks</summary><p></p></details>
<details><summary>Implement failure detection during deployment</summary><p></p></details>
<details><summary>Implement failure event handling/response</summary><p></p></details>
<details><summary>Ensure that resources/components/processes exist to react to failures during deployment</summary><p></p></details>
<details><summary>Look for exit codes on each event of the deployment</summary><p></p></details>
<details><summary>Map errors to different points of deployment</summary><p></p></details>