# home-lab
Home lab projects and reports focused on security monitoring, networking, troubleshooting, and incident investigation.
Just learning how to apply technical foundations.
## Area of Focus
- Network configuration and troubleshooting
- System logging and security monitoring
- Alert triage and evidence-based investigation
- Detection testing and validation
- Clear technical documentation and reporting
## Project Reports
1. PC Build

Designed and assembled a custom Windows 11 Pro workstation to support cybersecurity training, virtualization, technical projects, and daily computing. This report documents hardware selection, component compatibility, physical assembly, UEFI configuration, operating system installation, driver troubleshooting, security settings, and thermal validation.

2. Home Lab Configuration

Built and configured a personal cybersecurity monitoring environment using Oracle VirtualBox, Ubuntu Server, Wazuh, Splunk, Sysmon, Nmap, and Wireshark. This report covers virtual networking, Linux server administration, endpoint log collection, security monitoring integration, network scanning, troubleshooting, and validation of the completed environment.

Key Skills: Virtualization, Network Configuration, Linux Administration, Security Monitoring, Log Collection, Network Analysis, Troubleshooting

3. SOC Investigation #1

Conducted a structured security investigation involving encoded PowerShell execution, temporary file creation, and an internal TCP connection. Correlated endpoint events, Wazuh alerts, Splunk searches, file evidence, and Wireshark packet captures to determine the nature and scope of the observed activity. The investigation identified authorized, benign activity, assessed detection accuracy, documented appropriate response decisions, and verified case closure.

Key Skills: SOC Investigation, Alert Triage, Incident Analysis, Log Correlation, PowerShell Analysis, Network Traffic Analysis, Evidence Preservation, Technical Reporting
## Lab Overview
The cybersecurity home lab operates on a custom-built Windows 11 Pro workstation running Oracle VirtualBox. An Ubuntu Server virtual machine hosts the Wazuh security monitoring platform, while the Windows workstation generates endpoint telemetry through Sysmon and the Wazuh agent.

Splunk provides an independent method for searching Windows event logs, and Wireshark and Nmap support network traffic analysis and authorized network discovery.

The environment was designed to develop practical skills in systems administration, network operations, security monitoring, troubleshooting, and incident investigation. Future projects will expand its capabilities and document additional security investigations.
## Scope
The projects documented here are learning exercises conducted in my own home lab or another explicitly authorized environment. Findings are specific to the systems and conditions tested.
