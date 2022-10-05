# Domain 3: Monitoring and Logging - 15%
## Determine how to set up the aggregation, storage, and analysis of logs and metrics
<details><summary>Implement and configure distributed logs collection and processing (e.g., agents, syslog, flumed, CW agent)</summary><p></p></details>
<details><summary>Aggregate logs (e.g., Amazon S3, CW Logs, intermediate systems (EMR), Kinesis FH – Transformation, ELK/BI)</summary><p></p></details>
<details><summary>Implement custom CW metrics, Log subscription filters</summary><p></p></details>
<details><summary>Manage Log storage lifecycle (e.g., CW to S3, S3 lifecycle, S3 events)</summary><p></p></details>

## Apply concepts required to automate monitoring and event management of an environment
<details><summary>Parse logs (e.g., Amazon S3 data events/event logs/ELB/ALB/CF access logs) and correlate with other alarms/events (e.g., CW events to AWS Lambda) and take appropriate action</summary><p></p></details>
<details><summary>Use CloudTrail/VPC flow logs for detective control (e.g., CT, CW log filters, Athena, NACL or WAF rules) and take dependent actions (AWS step) based on error handling logic (state machine)</summary><p></p></details>
<details><summary>Configure and implement Patch/inventory/state management using ESM (SSM), Inspector, CodeDeploy, OpsWorks, and CW agents</summary>
<p>
* EC2 retirement/maintenance
</p>
</details>
<details><summary>Handle scaling/failover events (e.g., ASG, DB HA, route table/DNS update, Application Config, Auto Recovery, PH dashboard, TA)</summary><p></p></details>
<details><summary>Determine how to automate the creation of monitoring</summary><p></p></details>

## Apply concepts required to audit, log, and monitor operating systems, infrastructures, and applications
<details><summary>Monitor end to end service metrics (DDB/S3) using available AWS tools (X-ray with EB and Lambda)</summary><p></p></details>
<details><summary>Verify environment/OS state through auditing (Inspector), Config rules, CloudTrail (process and action), and AWS APIs</summary><p></p></details>
<details><summary>Enable, configure, and analyze custom metrics (e.g., Application metrics, memory, KCL/KPL) and take action</summary><p></p></details>
<details><summary>Ensure container monitoring (e.g., task state, placement, logging, port mapping, LB)</summary><p></p></details>
<details><summary>Distinguish between services that enable service level or OS level monitoring</summary>
<p>
* Example: AWS services that use OS agents (e.g., Inspector, SSM)
</p>
</details>

## Determine how to implement tagging and other metadata strategies
<details><summary>Segregate authority based on tagging (lifecycle stages – dev/prod) with Condition context keys</summary><p></p></details>
<details><summary>Utilize Amazon S3 system/user-defined metadata for classification and automation</summary><p></p></details>
<details><summary>Design and implement tag-based deployment groups with CodeDeploy</summary><p></p></details>
<details><summary>Best practice for cost allocation/optimization with tagging</summary><p></p></details>