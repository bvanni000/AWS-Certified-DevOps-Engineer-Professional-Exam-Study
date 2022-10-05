# Domain 5: Incident and Event Response
## Troubleshoot issues and determine how to restore operations
* Given an issue, evaluate how to narrow down the unhealthy components as quickly as possible
* Given an increase in load, determine what steps to take to mitigate the impact
* Determine the causes and impacts of a failure
  * Example: Deployment, operations
* Determine the best way to restore operations after a failure occurs
* Investigate and correlate logged events with application components
  * Example: application source code

## Determine how to automate event management and alerting
* Set up automated restores from backup in the event of a catastrophic failure
* Set up methods to deliver alerts and notifications that are appropriate for different types of events
* Assess the quality/actionability of alerts
* Configure metrics appropriate to an application’s SLAs
* Proactively update limits

## Apply concepts required to implement automated healing
* Set up the correct scaling strategy to enable auto-healing when a failure occurs (e.g., with Auto Scaling policies)
* Use the correct rollback strategy to avoid impact from failed deployments
* Configure Route 53 to ensure cross-Region failover
* Detect and respond to maintenance or Spot termination events

## Apply concepts required to set up event-driven automated actions
* Configure Lambda functions or CloudWatch actions to implement automated actions
* Set up CloudWatch event rules and/or Config rules and targets
* Use AWS Systems Manager or Step Functions to coordinate components (e.g., Lambda, use maintenance windows)
* Configure a build/roll-out process to automatically respond to critical software updates