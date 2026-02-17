| [Home](../README.md) |
|--------------------------------------------|

# Usage

Refer to [Simulate Scenario documentation](https://github.com/fortinet-fortisoar/solution-pack-soc-simulator/blob/develop/docs/solution-pack-guide.md) to understand how to simulate and reset scenarios.

To understand the process FortiSOAR follows to respond to IOC processing and automation, this solution pack includes a scenario — **IOC Processing** — that demonstrates the end-to-end workflow for ingesting, extracting, and acting on Indicators of Compromise (IOCs) from alert attachments.

## Scenario: IOC Processing Alert

This scenario generates an example alert of type other. 

Navigate to the demo alert and note the following:
- The demo alert created is an example of a default email ingestion using the Data Ingestion feature of Exchange connector.
- Alert is linked to attachments which has sample IOCs.


This solution pack includes a playbook called **`Auto IoC Ingest - Review and Send Block to Devices`**, which can be launched manually from the **Alerts** page.

The playbook performs the following automated steps:

---

### 1. Extraction
The playbook extracts Indicators of Compromise (IoCs) from the alert attachment.

---

### 2. Review
The extracted IoCs are presented for user review, where the user selects the desired action for each indicator.

#### Available Actions

**Block Automatically**
- Creates IoC records
- Sets the indicator status to **Blocked**
- Sends the blocked IoCs to downstream blocking playbooks

**Block Manually**
- Creates IoC records without modifying the status
- Allows users to review and update the status later

**Reject**
- No action is taken on the selected IoCs


### How to Use

- Deploy the solution pack and ensure prerequisites are installed.
- Use the included scenario to simulate IOC processing by generating a test alert with an attachment.
- Review the extracted indicators and observe the automated or manual blocking actions.
- Customize the playbooks as needed for your environment.


> For more details on each playbook and scenario, refer to the [Contents](./contents.md) documentation.
