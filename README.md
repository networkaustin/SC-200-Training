# SC-200-Objectives
*A list of exam objectives and links to where they are explained in Microsoft Learn*

## Skill Weighting
- Manage a security operations environment (25–30%)
- Configure protections and detections (15–20%)
- Manage incident response (35–40%)
- Perform threat hunting (15–20%)

## Manage a Security Operations Environment (25–30%)
### Configure Settings in Microsoft Defender XDR
- Configure a connection from Defender XDR to a Sentinel workspace
	- https://learn.microsoft.com/en-us/azure/sentinel/connect-microsoft-365-defender?tabs=MDE
- Configure alert and vulnerability notification rules
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender/configure-email-notifications?view=o365-worldwide
- Configure Microsoft Defender for Endpoint advanced features
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/advanced-features?view=o365-worldwide
- Configure endpoint rules settings, including indicators and web content filtering
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/manage-indicators?view=o365-worldwide
- Manage automated investigation and response capabilities in Microsoft Defender XDR
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender/m365d-autoir?view=o365-worldwide
- Configure automatic attack disruption in Microsoft Defender XDR
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender/automatic-attack-disruption?view=o365-worldwide
### Manage Assets and Environments
- Configure and manage device groups, permissions, and automation levels in Microsoft Defender for Endpoint
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/rbac?view=o365-worldwide
- Identify and remediate unmanaged devices in Microsoft Defender for Endpoint
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/device-discovery?view=o365-worldwide
- Manage resources by using Azure Arc
	- https://learn.microsoft.com/en-us/azure/azure-arc/overview
- Connect environments to Microsoft Defender for Cloud (by using multi-cloud account management)
	- https://learn.microsoft.com/en-us/azure/defender-for-cloud/multicloud
- Discover and remediate unprotected resources by using Defender for Cloud
	- https://learn.microsoft.com/en-us/azure/defender-for-cloud/review-security-recommendations
- Identify and remediate devices at risk by using Microsoft Defender Vulnerability Management
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender-vulnerability-management/tvm-security-recommendation?view=o365-worldwide
### Design and Configure a Microsoft Sentinel Workspace
- Plan a Microsoft Sentinel workspace
	- https://learn.microsoft.com/en-us/azure/sentinel/deploy-overview
- Configure Microsoft Sentinel roles
	- https://learn.microsoft.com/en-us/azure/sentinel/roles#roles-and-permissions-for-working-in-microsoft-sentinel
- Specify Azure RBAC roles for Microsoft Sentinel configuration
	- https://learn.microsoft.com/en-us/azure/sentinel/roles#role-and-permissions-recommendations
- Design and configure Microsoft Sentinel data storage, including log types and log retention
	- https://learn.microsoft.com/en-us/azure/sentinel/best-practices-workspace-architecture
- Manage multiple workspaces by using Workspace manager and Azure Lighthouse
	- https://learn.microsoft.com/en-us/azure/lighthouse/how-to/view-manage-customers
### Ingest Data Sources in Microsoft Sentinel
- Identify data sources to be ingested for Microsoft Sentinel
	- https://learn.microsoft.com/en-us/azure/sentinel/data-connectors-reference
- Configure and use Microsoft connectors for Azure resources, including Azure Policy and diagnostic settings
	- https://learn.microsoft.com/en-us/azure/sentinel/connect-data-sources
- Configure bidirectional synchronization between Microsoft Sentinel and Microsoft Defender XDR
	- https://learn.microsoft.com/en-us/azure/sentinel/microsoft-365-defender-sentinel-integration
- Configure bidirectional synchronization between Microsoft Sentinel to Microsoft Defender for Cloud
	- https://learn.microsoft.com/en-us/azure/sentinel/ingest-defender-for-cloud-incidents
- Plan and configure Syslog and Common Event Format (CEF) event collections
	- https://learn.microsoft.com/en-us/azure/sentinel/connect-cef-syslog-options
- Plan and configure collection of Windows Security events by using data collection rules, including Windows Event Forwarding (WEF)
	- https://learn.microsoft.com/en-us/azure/sentinel/data-connectors/windows-security-events-via-ama
- Configure threat intelligence connectors, including platform, TAXII, upload indicators API, and MISP
	- https://learn.microsoft.com/en-us/azure/sentinel/connect-threat-intelligence-tip
- Create custom log tables in the workspace to store ingested data
	- https://learn.microsoft.com/en-us/azure/sentinel/connect-custom-logs?tabs=DCG
## Configure Protections and Detections (15–20%)
### Configure Protections in Microsoft Defender Security Technologies
- Configure policies for Microsoft Defender for Cloud Apps
	- https://learn.microsoft.com/en-us/defender-cloud-apps/app-governance-app-policies-overview
- Configure policies for Microsoft Defender for Office
	- https://learn.microsoft.com/en-us/microsoft-365/security/office-365-security/recommended-settings-for-eop-and-office365?view=o365-worldwide
- Configure security policies for Microsoft Defender for Endpoints, including attack surface reduction (ASR) rules
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/attack-surface-reduction?view=o365-worldwide
- Configure cloud workload protections in Microsoft Defender for Cloud
	- https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-cloud-introduction#protect-cloud-workloads
### Configure Detection in Microsoft Defender XDR
- Configure and manage custom detections
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender/custom-detection-rules?view=o365-worldwide
- Configure alert tuning
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender/investigate-alerts?view=o365-worldwide#tune-an-alert
- Configure deception rules in Microsoft Defender XDR
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender/configure-deception?view=o365-worldwide#create-and-modify-deception-rules
### Configure Detections in Microsoft Sentinel
- Classify and analyze data by using entities
	- https://learn.microsoft.com/en-us/azure/sentinel/entities
- Configure scheduled query rules, including KQL
	- https://learn.microsoft.com/en-us/azure/sentinel/detect-threats-custom
- Configure near-real-time (NRT) query rules, including KQL
	- https://learn.microsoft.com/en-us/azure/sentinel/create-nrt-rules
- Manage analytics rules from Content hub
	- https://learn.microsoft.com/en-us/azure/sentinel/sentinel-solutions-deploy
- Configure anomaly detection analytics rules
	- https://learn.microsoft.com/en-us/azure/sentinel/soc-ml-anomalies
- Configure the Fusion rule
	- https://learn.microsoft.com/en-us/azure/sentinel/configure-fusion-rules
- Query Microsoft Sentinel data by using ASIM parsers
	- https://learn.microsoft.com/en-us/azure/sentinel/normalization-about-parsers
- Manage and use threat indicators
	- https://learn.microsoft.com/en-us/azure/sentinel/work-with-threat-indicators
## Manage Incident Response (35–40%)
### Respond to Alerts and Incidents in Microsoft Defender XDR
- Investigate and remediate threats to Microsoft Teams, SharePoint Online, and OneDrive
	- https://learn.microsoft.com/en-us/microsoft-365/security/office-365-security/office-365-ti?view=o365-worldwide
- Investigate and remediate threats in email by using Microsoft Defender for Office
	- https://learn.microsoft.com/en-us/microsoft-365/security/office-365-security/office-365-ti?view=o365-worldwide
- Investigate and remediate ransomware and business email compromise incidents identified by automatic attack disruption
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender-business/mdb-attack-disruption?view=o365-worldwide
- Investigate and remediate compromised entities identified by Microsoft Purview data loss prevention (DLP) policies
	- https://learn.microsoft.com/en-us/purview/dlp-learn-about-dlp
- Investigate and remediate threats identified by Microsoft Purview insider risk policies
	- https://learn.microsoft.com/en-us/purview/insider-risk-management
- Investigate and remediate alerts and incidents identified by Microsoft Defender for Cloud
	- https://learn.microsoft.com/en-us/azure/defender-for-cloud/managing-and-responding-alerts
- Investigate and remediate security risks identified by Microsoft Defender for Cloud Apps
	- https://learn.microsoft.com/en-us/defender-cloud-apps/investigate
- Investigate and remediate compromised identities in Microsoft Entra ID
	- https://learn.microsoft.com/en-us/entra/id-protection/howto-identity-protection-investigate-risk
- Investigate and remediate security alerts from Microsoft Defender for Identity
	- https://learn.microsoft.com/en-us/defender-for-identity/alerts-overview
- Manage actions and submissions in the Microsoft Defender portal
	- https://learn.microsoft.com/en-us/microsoft-365/security/office-365-security/submissions-admin?view=o365-worldwide
### Respond to Alerts and Incidents Identified by Microsoft Defender for Endpoint
- Investigate timeline of compromised devices
	- https://learn.microsoft.com/en-us/defender-for-identity/investigate-assets
- Perform actions on the device, including live response and collecting investigation packages
	- https://learn.microsoft.com/en-us/defender-for-identity/remediation-actions
- Perform evidence and entity investigation
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/investigate-incidents?view=o365-worldwide
### Enrich Investigations by Using other Microsoft Tools
- Investigate threats by using unified audit Log
	- https://learn.microsoft.com/en-us/training/modules/investigate-threats-using-audit-in-microsoft-365-defender-microsoft-purview-standard/
	- https://learn.microsoft.com/en-us/purview/audit-new-search
- Investigate threats by using Content Search
	- https://learn.microsoft.com/en-us/training/modules/investigate-threats-with-content-search-in-microsoft-purview/
		- https://learn.microsoft.com/en-us/purview/ediscovery-content-search-overview
- Perform threat hunting by using Microsoft Graph activity logs
	- https://learn.microsoft.com/en-us/graph/api/resources/security-api-overview?view=graph-rest-1.0
### Manage Incidents in Microsoft Sentinel
- Triage incidents in Microsoft Sentinel
	- https://learn.microsoft.com/en-us/azure/sentinel/investigate-incidents
- Investigate incidents in Microsoft Sentinel
	- https://learn.microsoft.com/en-us/azure/sentinel/investigate-incidents
- Respond to incidents in Microsoft Sentinel
	- https://learn.microsoft.com/en-us/azure/sentinel/investigate-incidents#audit-and-comment-on-incidents
	- https://learn.microsoft.com/en-us/azure/sentinel/automation
### Configure Security Orchestration, Automation, and Response (SOAR) in Microsoft Sentinel
- Create and configure automation rules
	- https://learn.microsoft.com/en-us/azure/sentinel/create-manage-use-automation-rules
- Create and configure Microsoft Sentinel playbooks
	- https://learn.microsoft.com/en-us/azure/sentinel/automate-responses-with-playbooks
- Configure analytic rules to trigger automation
	- https://learn.microsoft.com/en-us/azure/sentinel/playbook-triggers-actions
- Trigger playbooks manually from alerts and incidents
	- https://learn.microsoft.com/en-us/azure/sentinel/playbook-triggers-actions
- Run playbooks on On-premises resources
	- https://learn.microsoft.com/en-us/azure/sentinel/automate-responses-with-playbooks
## Perform Threat Hunting (15–20%)
### Hunt for Threats by Using KQL
- Identify threats by using Kusto Query Language (KQL)
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender/advanced-hunting-query-language?view=o365-worldwide
- Interpret threat analytics in the Microsoft Defender portal
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender/threat-analytics?view=o365-worldwide
- Create custom hunting queries by using KQL
	- https://learn.microsoft.com/en-us/microsoft-365/security/defender/advanced-hunting-custom-functions?view=o365-worldwide
### Hunt for Threats by Using Microsoft Sentinel
- Analyze attack vector coverage by using the MITRE ATT&CK in Microsoft Sentinel
	- https://learn.microsoft.com/en-us/azure/sentinel/mitre-coverage
- Customize content gallery hunting queries
	- https://learn.microsoft.com/en-us/azure/sentinel/sentinel-solutions-deploy
- Use hunting bookmarks for data investigations
	- https://learn.microsoft.com/en-us/azure/sentinel/bookmarks
- Monitor hunting queries by using Livestream
	- https://learn.microsoft.com/en-us/azure/sentinel/livestream
- Retrieve and manage archived log data
	- https://learn.microsoft.com/en-us/azure/sentinel/restore
- Create and manage search jobs
	- https://learn.microsoft.com/en-us/azure/sentinel/search-jobs
### Analyze and Interpret Data by Using Workbooks
- Activate and customize Microsoft Sentinel workbook templates
	- https://learn.microsoft.com/en-us/azure/sentinel/monitor-your-data
- Create custom workbooks that include KQL
	- https://learn.microsoft.com/en-us/azure/sentinel/monitor-your-data
- Configure visualizations
	- https://learn.microsoft.com/en-us/azure/sentinel/get-visibility
