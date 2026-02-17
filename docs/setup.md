| [Home](../README.md) |
|--------------------------------------------|

# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.
2. From the list of solution pack that appears, search for and select `IOC Processing`.
3. Click the `IOC Processing` solution pack card.
4. Click **Install** on the bottom to begin installation.

## Prerequisites

The `IOC Processing` solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| **Solution Pack Name** | **Purpose**   |
| :--------------------- | :--------------------------------------- |
| SOAR Framework | Dependency for core SOAR functionalities |
| SOC Simulator | Provides simulation capabilities for SOC scenarios |

# Configuration

For optimal performance of `IOC Processing` solution pack, you can install and configure the connectors that help with the following:

>**Example**:
>* Threat intelligence connectors to enrich context of a given indicator
>    * To configure and use the VirusTotal connector as a source of threat intelligence, refer to [Configuring Virus Total](https://docs.fortinet.com/document/fortisoar/2.1.0/virustotal/166/virustotal-v2-1-0#Configuration_parameters)
>* An email ingestion process to periodically read email from a designated inbox and convert them into alerts in FortiSOAR
>    * To configure and use the Microsoft Exchange connector for email ingestion, refer to [Configuring Exchange Connector](https://docs.fortinet.com/document/fortisoar/3.4.0/exchange/1/exchange-v3-4-0#Configuring_the_connector)