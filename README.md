# Release Information

- **Version**: 1.0.0

- **Certified**: Yes

- **Publisher**: Fortinet  

- **Compatibility**: 8.0.0 and later

# Overview

The **IOC Processing** Solution Pack streamlines the transition from raw email-based intelligence to active security posture. It automates the ingestion and parsing of email attachments, enabling SOC Analysts and CSEs to process threat indicators without manual data entry.

### Core Functionality

<!-- - **Automated Ingestion:** Integrates with **Exchange** or **SMTP** connectors to monitor mailboxes and convert incoming emails into FortiSOAR *Alerts* and uploading file attachments as linked FortiSOAR *Attachment* records. -->

- **Multi-Format Extraction:** Utilizes the **File Content Extraction** connector to identify full-spectrum indicators (**IP**, **Domain**, **URL**, **Hash**) from supported file types, including `.zip` archives.

- **Analyst-Driven Triage:** Features a manually-triggered playbook that allows users to review findings and select a response:
    - **Block:** Push indicators to the security fabric.
    - **Record:** Log IoC records for future monitoring.
    - **Reject:** Dismiss irrelevant or false-positive data.

<!-- - **Enrichment Integration:** Can leverage user-configured connectors (e.g., **VirusTotal**) to provide immediate context and risk scoring for all extracted indicators. -->

### Operational Benefits

- **Controlled Remediation:** Maintains a "Human-in-the-Loop" model, ensuring that automated ingestion is balanced with expert validation before any blocking action occurs.

- **Standardized Workflow:** Replaces ad-hoc attachment processing with a consistent, repeatable framework for handling intelligence digests.

- **Auditable Oversight:** Every analyst decision is recorded within the platform, providing a transparent audit trail for compliance and reporting.

## Next Steps

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Contents](./docs/contents.md) | [Usage](./docs/usage.md) |
|----------------------------------------------|------------------------------------------------|--------------------------------|--------------------------|

