| **Sl. No.** | **Rule File Name**               | **Description**                                                               | **Windows Rule ID(s)** | **Core Topic**                 |
| ----------- | -------------------------------- | ----------------------------------------------------------------------------- | ---------------------- | ------------------------------ |
| 1           | `0575-win-base_rules.xml`        | Base Windows event rules (startup, shutdown, login status, etc.)              | 60000–60099            | General Windows Events         |
| 2           | `0580-win-security_rules.xml`    | Windows Security Log (logon, group changes, account lockouts)                 | 60100–60599            | Windows Event Channel Rules    |
| 3           | `0585-win-application_rules.xml` | Windows Application Log (app crashes, errors, service issues)                 | 60600–61099            | Windows Event Channel Rules    |
| 4           | `0590-win-system_rules.xml`      | System events (service start/stop, shutdown, errors)                          | 61100–61599            | Windows Event Channel Rules    |
| 5           | `0595-win-sysmon_rules.xml`      | Sysmon logs (process creation, registry access, DNS queries, etc.)            | 61600–62099            | Sysmon Monitoring              |
| 6           | `0600-win-wdefender_rules.xml`   | Microsoft Defender antivirus detections, threats, scan logs                   | 62100–62599            | Antivirus and Windows Defender |
| 7           | `0602-win-wfirewall_rules.xml`   | Windows Firewall events (rule changes, status updates)                        | 67001–67010            | Windows Firewall Rules         |
| 8           | `0605-win-mcafee_rules.xml`      | McAfee antivirus logs (virus alerts, scans, engine updates)                   | 62600–63099            | Antivirus and Windows Defender |
| 9           | `0610-win-ms_logs_rules.xml`     | Windows logs (Update logs, Compatibility Assistant, ETW)                      | 63100–63599            | Windows Event Channel Rules    |
| 10          | `0615-win-ms-se_rules.xml`       | Microsoft Security Essentials (legacy AV)                                     | 63600–64099            | Antivirus and Windows Defender |
| 11          | `0620-win-generic_rules.xml`     | General/misc Windows detections (system-level alerts not covered elsewhere)   | 64100–64599            | General Windows Events         |
| 12          | `0840-win_event_channel.xml`     | Monitors Event Channel logs (RDP logins, service creation, scheduled tasks)   | 92650–92700            | Windows Event Channel Rules    |
| 13          | `0915-win-powershell_rules.xml`  | Rules detect suspicious PS activity, such as script execution, pipeline cmds, and encoded commands | 91801–92000            | PowerShell Monitoring          |
| 14          | `0601-win-vipre-_rules.xml`      | Rules for VIPRE antivirus logs on windows endpoints. It's comes under ID '60600' (0585-win-application_rules.xml)  | 90499-90600    | VIPRE Antivirus     |
| 15          | `0570-sca_rules.xml`             | Handles alerts from Security Configuration Assessment (SCA) scans             | 19000-19015            |  SCA scan rules                |
| 16          | `0755-office365_rules.xml`       | Correlates with Microsoft Office 365 audit logs                               | 91531 - 91650          |  Office 365 rules              |
| 17          | `0220-msauth_rules.xml`          | Windows authentication log events (e.g., login failed, audit log clear, replay attacks on DC)  | 18118 – 18171   |  Windows Auth   |
| 18          | `0230-ms-se_rules.xml`           | Microsoft Security Essentials log events (legacy Defender)        |  7701-  | Microsoft Security Essentials rules   |
| 19          | `0330-sysmon_rules.xml`          | Sysmon event log rules (process creation, network connections, registry events) via Windows Event Log   | 184665-  |    Sysmon rules |
| 20         | `0430-ms_wdefender_rules.xml`     | Windows Defender (Operational channel) alerts (detections, scanning actions)  |  83000 - 83199  |    Windows defender rules  |
| 21      | `0435-ms_logs_rules.xml`            |  Microsoft Event Log Service startup and log service operations      | 83200 - 83299    |  MS Event Log rules    | 
| 22      | `0440-ms_sqlserver_rules.xml`      |  SQL Server logs (Windows-based SQL Server instance events and errors)  |   85000 - 85499   | SQL Server rules     |  
| 23      | `0800-sysmon_id_1.xml`              | Sysmon Event ID 1 rules                                          | 92000 - 92100    |  Sysmon Monitoring  |
| 24      | `0810-sysmon_id_3.xml`               |  Sysmon Event ID 3 rules                                        | 92101 - 92150     | Sysmon Monitoring  |
| 25      | `0820-sysmon_id_7.xml`               |  Sysmon Event ID 7 rules                                        |  92151 - 92199     | Sysmon Monitoring  |
| 26      | `0830-sysmon_id_11.xml`               |  Sysmon Event ID 11 rules                                        |  92200 - 92299     | Sysmon Monitoring  |
| 27      | `0860-sysmon_id_13.xml`               |  Sysmon Event ID 13 rules                                        |  92300 - 92399     | Sysmon Monitoring  |
| 28      | `0870-sysmon_id_8.xml`               |  Sysmon Event ID 8 rules                                        |  92400 - 92499     | Sysmon Monitoring  |
| 29      | `0910-ms-exchange-proxylogon_rules.xml`        |  Microsoft Exchange ProxyLogon vulnerabilities   |  91000 - 91008     | Windows Microsoft Exchange Server  |
| 30      | `0945-sysmon_id_10.xml`               |  Sysmon Event ID 10 rules                                        |  92900-     | Sysmon Monitoring  |
| 31      | `0950-sysmon_id_20.xml`               |  Sysmon Event ID 20 rules                                        |  89501-     | Sysmon Monitoring  |
| 32      | `0995-microsoft-graph_rules.xml`       | contains detection logic for logs coming from the Microsoft Graph API |  99500 - 99700    | cloud monitoring and Microsoft 365  |
| 33      | `0520-vulnerability-detector_rules.xml`| used to analyze vulnerability scan results generated by Wazuh's built-in Vulnerability Detector module |  23501-     | Wazuh Vulnerability Detector for Windows, linux and macos  |
| 34      | `0190-ms_ftpd_rules.xml`       | detect events and suspicious behavior from FTP servers running on Microsoft platforms |  11500-    | Windows Server (MS FTP Server )  |
| 35      | `0110-ms_dhcp_rules.xml`       | rule file that analyzes logs from Microsoft DHCP Server |  6300-    | Microsoft Windows 2003 ipv4, Windows 2008 ipv4/ipv6 DHCP rules  |
| 36      | `0050-ms-exchange_rules.xml`       | detect events, errors, and suspicious behavior within Microsoft Exchange Server logs |  3800-    | Microsoft Exchange Server  |










