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
| 18          | `0230-ms-se_rules.xml`           | Microsoft Security Essentials log events (legacy Defender)        |    |    |
| 19          | `0330-sysmon_rules.xml`          | Sysmon event log rules (process creation, network connections, registry events) via Windows Event Log   |   |     |
| 20         | `0430-ms_wdefender_rules.xml`     | Windows Defender (Operational channel) alerts (detections, scanning actions)  |    |      |
| 21      | `0435-ms_logs_rules.xml`            |  Microsoft Event Log Service startup and log service operations      |     |      | 
| 22      | `0440-ms_sqlserver_rules.xml`      |  SQL Server logs (Windows-based SQL Server instance events and errors)  |      |      |  
