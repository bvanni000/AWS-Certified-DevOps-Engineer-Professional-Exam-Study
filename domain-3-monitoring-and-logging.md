# Domain 3: Monitoring and Logging

## Determine how to set up the aggregation, storage, and analysis of logs and metrics
* Implement and configure distributed logs collection and processing (e.g., agents, syslog, flumed, CW agent)
* Aggregate logs (e.g., Amazon S3, CW Logs, intermediate systems (EMR), Kinesis FH – Transformation, ELK/BI)
* Implement custom CW metrics, Log subscription filters
* Manage Log storage lifecycle (e.g., CW to S3, S3 lifecycle, S3 events)

## Apply concepts required to automate monitoring and event management of an environment
* Parse logs (e.g., Amazon S3 data events/event logs/ELB/ALB/CF access logs) and correlate with other alarms/events (e.g., CW events to AWS Lambda) and take appropriate action
* Use CloudTrail/VPC flow logs for detective control (e.g., CT, CW log filters, Athena, NACL or WAF rules) and take dependent actions (AWS step) based on error handling logic (state machine)
* Configure and implement Patch/inventory/state management using ESM (SSM), Inspector, CodeDeploy, OpsWorks, and CW agents
  * EC2 retirement/maintenance
* Handle scaling/failover events (e.g., ASG, DB HA, route table/DNS update, Application Config, Auto Recovery, PH dashboard, TA)
* Determine how to automate the creation of monitoring

## Apply concepts required to audit, log, and monitor operating systems, infrastructures, and applications
* Monitor end to end service metrics (DDB/S3) using available AWS tools (X-ray with EB and Lambda)
* Verify environment/OS state through auditing (Inspector), Config rules, CloudTrail (process and action), and AWS APIs
* Enable, configure, and analyze custom metrics (e.g., Application metrics, memory, KCL/KPL) and take action
* Ensure container monitoring (e.g., task state, placement, logging, port mapping, LB)
* Distinguish between services that enable service level or OS level monitoring
  * Example: AWS services that use OS agents (e.g., Inspector, SSM)

## Determine how to implement tagging and other metadata strategies
* Segregate authority based on tagging (lifecycle stages – dev/prod) with Condition context keys
* Utilize Amazon S3 system/user-defined metadata for classification and automation
* Design and implement tag-based deployment groups with CodeDeploy
* Best practice for cost allocation/optimization with tagging