# Windows-Firewall-Task
A step-by-step configuration and testing of custom firewall rules on Windows, including blocking Telnet (port 23) and documenting the process.


## Objective
Configure and test basic firewall rules to allow or block traffic on Windows.

## Steps Performed
1. Opened Windows Firewall with Advanced Security.
2. Listed current inbound firewall rules.
3. Created a new inbound rule to block TCP port 23 (Telnet).
4. Tested the rule using the `telnet` command — connection blocked successfully.
5. Removed the test block rule to restore the original firewall state.
6. Documented all steps, commands, and screenshots.

## Files Included
- **windows_firewall_report.pdf** — Detailed report with steps, commands, and screenshot.
- **Screenshot 2025-08-08 140114.png** — Proof of Telnet block test.
- **FirewallRules_Inbound.txt** — Exported inbound rules list.

## Summary
This task demonstrates how Windows Firewall filters traffic based on custom rules and how to test these rules effectively.
