| [Home](../README.md) |
|--------------------------------------------|

# Usage

Refer to [Simulate Scenario documentation](https://github.com/fortinet-fortisoar/solution-pack-soc-simulator/blob/develop/docs/solution-pack-guide.md) to understand how to simulate and reset scenarios.

To understand the process FortiSOAR follows to respond to IOC processing and automation, this solution pack includes a scenario — **IOC Processing** — that demonstrates the end-to-end workflow for ingesting, extracting, and acting on Indicators of Compromise (IOCs) from alert attachments.

## Scenario: IOC Processing Alert

This scenario generates an alert with an attachment containing sample IOCs. The solution pack automates the following steps:

1. **Alert Generation**: An alert is created with an attachment that includes IOCs (such as IPs, domains, URLs).
2. **Extraction**: The playbook `Auto Ingest IoCs > Extract Indicators from Attachment` extracts indicators from the attachment.
3. **Review and Block**: The playbook `Auto IoC Ingest - Review and Send Block to Devices` reviews the extracted IOCs and can automatically or manually block them on integrated devices.
4. **Scenario Automation**: The scenario playbook `Scenario - Generating Alert with IOC attachments` demonstrates the full automation, from alert creation to IOC processing.

### How to Use

- Deploy the solution pack and ensure prerequisites are installed.
- Use the included scenario to simulate IOC processing by generating a test alert with an attachment.
- Review the extracted indicators and observe the automated or manual blocking actions.
- Customize the playbooks as needed for your environment.

> For more details on each playbook and scenario, refer to the [Contents](./contents.md) documentation.