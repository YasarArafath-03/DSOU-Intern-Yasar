# Wazuh Alert Triage Template

| Alert ID | Timestamp           | Source IP     | Host           | Rule Description             | Urgency | Next Action                             | Status        |
| -------- | ------------------- | ------------- | -------------- | ---------------------------- | ------- | --------------------------------------- | ------------- |
| 5715     | 2026-06-17 10:30:22 | 192.168.1.101 | DSOU-WIN-Yasar | Windows login failed         | Medium  | Check for brute force attempts          | Investigating |
| 61603    | 2026-06-17 10:35:10 | 192.168.1.101 | DSOU-WIN-Yasar | Suspicious process execution | High    | Review process lineage and command line | Escalated     |
| 1002     | 2026-06-17 10:40:05 | 192.168.1.101 | DSOU-WIN-Yasar | USB device inserted          | Low     | Verify authorized device                | Resolved      |

## Urgency Levels

* LOW: Informational, no immediate action required
* MEDIUM: Requires investigation, but not an emergency
* HIGH: Immediate attention required, potential security incident
* CRITICAL: Confirmed compromise, incident response initiated
