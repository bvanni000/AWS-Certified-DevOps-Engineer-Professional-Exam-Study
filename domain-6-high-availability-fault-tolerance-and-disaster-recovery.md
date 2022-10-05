# Domain 6: High Availability, Fault Tolerance, and Disaster Recovery
## Determine appropriate use of multi-AZ versus multi-Region architectures
* Determine deployment strategy based on HA/DR requirements
* Determine data replication strategy based on cost and durability requirements
* Determine infrastructure, platform, and services based on HA/DR requirements
* Design for HA/FT/DR based on service availability (i.e., global/regional/single AZ)

## Determine how to implement high availability, scalability, and fault tolerance
* Design deployment strategy to support HA/FT/scalability
* Assess statefulness of application infrastructure components
* Use load balancing to distribute traffic across multiple AZ/ASGs/instance types (spot/M4 vs C4) /targets
* Use appropriate caching solutions to improve availability and performance

## Determine the right services based on business needs (e.g., RTO/RPO, cost)
* Determine cost-effective storage solution for your application
  * Example: tiered, archival, EBS type, hot/cold
* Choose a database platform and configuration to meet business requirements
* Choose a cost-effective compute platform based on business requirements
  * Example: Spot
* Choose a deployment service/model based on business requirements
* Example: Code Deploy, Blue/Green deployment
* Determine when to use managed service vs. self-managed infrastructure (Docker on EC2 vs. ECS)

## Determine how to design and automate disaster recovery strategies
* Automate failure detection
* Automate components/environment recovery
* Choose appropriate deployment strategy for environment recovery
* Design automation to support failover in hybrid environment

## Evaluate a deployment for points of failure
* Determine appropriate deployment-specific health checks
* Implement failure detection during deployment
* Implement failure event handling/response
* Ensure that resources/components/processes exist to react to failures during deployment
* Look for exit codes on each event of the deployment
* Map errors to different points of deployment