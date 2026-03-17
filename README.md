# Release Information

- **Version**: 1.0.0

- **Certified**: Yes

- **Publisher**: Fortinet  

- **Compatibility**: 8.0.0 and later

# Overview

The **IOC Processing** Solution Pack converts email-based threat intelligence into actionable indicators inside FortiSOAR. It automatically ingests email attachments and extracts indicators for analysts to review and take appropriate action.

### Core Functionality

- **Multi-Format Extraction**: Utilizes the **File Content Extraction** connector to identify indicators (**IP**, **Domain**, **URL**, **Hash**) from supported file types, including `.zip` archives.

- **Analyst-Driven Triage**: Features a manually-triggered playbook that allows users to review findings and select a response:

    - **Block Automatically**: Create IoC records and push them to the security fabric.

    - **Block Manually**: Create IoC records to be reviewed later.

    - **Do Not Block**: Dismisses presented data and does not create IoC records.

### Operational Benefits

- **Controlled Remediation**: Maintains a *Human-in-the-Loop* model, ensuring that automated ingestion is balanced with expert validation before any blocking action occurs.

- **Standardized Workflow**: Replaces ad-hoc attachment processing with a consistent, repeatable framework for handling intelligence digests.

- **Auditable Oversight**: Every analyst decision is recorded within the platform, providing a transparent audit trail for compliance and reporting.

## Next Steps

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Contents](./docs/contents.md) | [Usage](./docs/usage.md) |
|----------------------------------------------|------------------------------------------------|--------------------------------|--------------------------|

