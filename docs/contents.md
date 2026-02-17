| [Home](../README.md) |
|--------------------------------------------|

# Contents

The `IOC Processing` solution pack contains the following resources.

## Connectors

|**Name**|**Description**|
| :- | :- |
| File Content Extraction | Utility to Extract Text, Artifacts and Metadata from almost any file. Internet connectivity is required for the connector to download dependent packages |

## Module Schema

|**Name**|**Description**|
| :- | :- |
|  |  |

## Global Variable

|**Name**|**Description**|
| :- | :- |
|  |  |

## Roles

|**Name**|**Description**|
| :- | :- |
|  |  |

## Record Set

|**Name**|**Description**|
| :- | :- |
| Scenario | This scenario generates an alert along with an attachment record. The attachment contains sample IOCs that need to be processed further and is linked to the alert. This enables execution of the subsequent workflow. |

## Playbook Collection

|Playbook Collection Name |
| :- |
| 10 - SP - IOC Processing |

**Playbook Name**|**Description**|
| :- | :- |
| Auto Ingest IoCs > Extract Indicators from Attachment | This playbook will extract the indicators from attachment. |
| Auto Ingest IoCs >> Create Indicators from Attachment | Create Indicators Form Attachments |
| Auto IoC Ingest - Review and Send Block to Devices | This playbook will ingest the indicators from attached file and will block it to devices. |
| Scenario - Generating Alert with IOC attachments | Create Alert which has attachment record link to it. |

>**Warning:** We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.
