| [Home](../README.md) |
|----------------------|

# Contents

The **IOC Processing** solution pack contains the following resources.

## Connectors

| Name                    | Description                                                                                                                                              |
|:------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------|
| File Content Extraction | Utility to Extract Text, Artifacts and Metadata from almost any file. Internet connectivity is required for the connector to download dependent packages |


## Scenario

| Name                 | Description                                                                                                                                                  |
|:---------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| IOC Processing Alert | This scenario generates an alert and an attachment record. The attachment contains sample IOCs that need to be processed further and is linked to the alert. |


## Playbook Collection

| Playbook Collection Name |
|:-------------------------|
| 10 - SP - IOC Processing |

| Playbook Name                                         | Description                                                                       |
|:------------------------------------------------------|:----------------------------------------------------------------------------------|
| Auto Ingest IoCs > Extract Indicators from Attachment | Extracts indicators from attachments.                                             |
| Auto Ingest IoCs >> Create Indicator Records          | Creates indicator records from attachments.                                       |
| Auto IOC Ingest- Review and Send IOC to Block         | Ingests indicators from the attached file and send them to be blocked on devices. |
| Scenario - Generating Alert with IOC attachments      | Creates an alert with an attachment record link to it.                            |

>[!WARNING]
>We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.

## Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|
